---
title: Continuous Static Analysis using Pronto
redirect_from: 2014/11/06/continuous-static-analysis/
hn: https://news.ycombinator.com/item?id=8568999
reddit: http://www.reddit.com/r/programming/comments/2li1ss/continuous_static_analysis_using_pronto/
---

Code quality and consistency is important. There are a ton of great open source tools and libraries that provide insights. For example: [Rubocop][rubocop] checks your style and [Brakeman][brakeman] scans for security vulnerabilities. You can run them easily and get a summary. But especially on a bigger codebase, that can take a while and result in a long list of issues.

What we really want is immediate feedback on the most recent code. That's where [Pronto][pronto] gem comes in. It takes [these various tools][runners] and only runs them on the specified changes. It also has various ways to output the result, including commenting on a pull request.

Let's go over on how to configure Pronto to run on every pull request with the help of [Travis CI][travis]. Start by adding Pronto to your Gemfile:

```
gem 'pronto'
gem 'pronto-rubocop'
gem 'pronto-flay'
```

Next, generate a new GitHub access token. Go to your `Settings -> Personal access tokens` or just follow [this link][token]. Pronto will only need repo/public_repo scopes to write comments, so you can uncheck everything else.

We'll need to make this token availabe to Pronto via environment variable. Go to the settings of your Travis CI build and configure it there. Name it GITHUB_ACCESS_TOKEN and set the value to the previously generated token. You can read more about how to do that in the official docs [here](http://docs.travis-ci.com/user/environment-variables/#Using-Settings). Note a security limitation: it will only be available to builds started by repo owners.

Now, the build script itself. There are better ways to do it, but for simplicity's sake let's just put it in .travis.yml:

```
script:
- 'export PULL_REQUEST_ID=${TRAVIS_PULL_REQUEST} &&
   bundle exec pronto run -f github_pr'
language: ruby
rvm:
- 1.9.3
- 2.1.1
```

That will run [Pronto][pronto] outputting result as comments on the pull request. By default, it checks the diff between the current HEAD and master.

That's it! Continous Static Analysis achieved. Create a pull request including some bad code and watch the magic happen. You can configure it similarly using other CI servers. At [Vinted][vinted], we run it on all our Ruby repositories with the help of [Jenkins][jenkins]. Hopefully, you'll also find it useful.

[pronto]: https://github.com/mmozuras/pronto
[travis]: https://travis-ci.org/
[jenkins]: https://jenkins-ci.org/
[rubocop]: https://github.com/bbatsov/rubocop
[brakeman]: https://github.com/presidentbeef/brakeman
[runners]: https://github.com/mmozuras/pronto#runners
[token]: https://github.com/settings/tokens/new
[vinted]: http://www.vinted.com/

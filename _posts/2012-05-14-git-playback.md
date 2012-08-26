---
layout: post
title: git playback
hn: http://news.ycombinator.com/item?id=3972107
---

It was a lovely Saturday afternoon... I just did a [code kata](http://en.wikipedia.org/wiki/Kata_(programming\)), but I was not entirely happy and not sure how to do it better. So I decided to look at how other developers tackled the same problem. Found a dozen repositories on [GitHub](https://github.com), but there were a couple of problems:

* A lot of them consisted of exactly one commit.
* Looking through commits on GitHub is not the most convenient solution in this case.

Code Katas are about the process, not about the result. I wanted to a nice way to view the steps, to see how someone got to the destination, and so the idea for git-playback was born.

So what exactly is git-playback? It's a bash script that goes through all commits in the current branch of repository and creates a slideshow using the specified files. Example output (use arrow keys to navigate):

[String Calculator Kata in Python](/static/string-calculator-kata-python.html)

You can find the source from which this playback was generated on [GitHub](https://github.com/mmozuras/string-calculator-kata-python).

If that got you interested, you can try it yourself:

    git clone git://github.com/mmozuras/git-playback.git
    cd /repository/you/want/to/playback
    sh /path/to/git-playback/git-playback file1 file2
    open playback.html

This post was written in the spirit of quick feedback. At this point, [git-playback] can still be greatly improved. Here's what I intend to add in the nearest feature:

* Add script options for things like: branch, style, font etc.
* Make the output nicer: line numbers, commit message and highlight changes.
* Create git-playback-jekyll. Look at how your jekyll-based website changed from commit to commit.

Would love to hear what you think about [git-playback]!

[git-playback]: https://github.com/mmozuras/git-playback

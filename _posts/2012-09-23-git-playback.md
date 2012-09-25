---
layout: post
title: git playback 0.2
hn: //news.ycombinator.com/item?id=4571253
---

The feedback after the [first post](/2012/05/14/git-playback) about [git-playback][repository] was amazing. I've been slowly improving it for the last couple of months and I'm pretty happy where it is right now. What's new:

*   Easier installation

    Just clone the repository and run `make install`. `git playback` command should become available.

*   Better transition

    The most requested feature on [Hacker News](//news.ycombinator.com/item?id=3972107) was a better transition between commits. I played around with multiple ways to do it and settled on the current one. I think that it works amazingly well. Have a look yourself (use left and right arrows to navigate):

    [String Calculator Kata in Python](/static/string-calculator-kata-python-v0.2.html)

    Hope you'll like it too. Learning how to [parse a diff](https://github.com/mmozuras/git-playback/blob/v0.2/git-playback.sh#L209) was really fun. I ended up using a CSS3 transitions for animation, but while the end code looks rather simple, there were a lot of bumps on the road. Huge thanks to [Erikas](//github.com/erikasb) for helping figure it out.

*   Styles

    [Hightlight.js](//softwaremaniacs.org/soft/highlight/en/) is used for syntax highlighting. It supports many different [styles](//softwaremaniacs.org/media/soft/highlight/test.html) and now it's pretty easy to use them with git-playback.

*   Output with commit message

    By default, output will contain a commit message, homewer it's still possible to have output without commit message by specifying --no-message flag:

    [No commit message and Zenburn](/static/string-calculator-kata-python-v0.2-zenburn.html)

*   No more dependency on internet connection

    The resulting playback file is completely standalone, you can copy it anywhere and it will still work.

Would love to hear what you think about [git-playback][repository]!

[repository]: //github.com/mmozuras/git-playback

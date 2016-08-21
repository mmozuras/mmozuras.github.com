---
layout: post
title: Vim - Putting arrows to use
redirect_from: 2012/08/21/vim-putting-arrows-to-use/
hn: //news.ycombinator.com/item?id=4414092
---

It's accepted among Vim users - arrow keys should be avoided at all possible cost. Using [hjkl is preferred](//www.catonmat.net/blog/why-vim-uses-hjkl-as-arrow-keys/) and is advantageous. You never have to leave the home row - that let's you be faster and it's more comfortable for your hands. As someone who's already had to deal with a little bit of wrist pain, not having to move my hands to arrow keys (and don't get me started about the mouse) is favorable, to say the least.

It's not something you get used to immediately though. When I started using Vim, trying to not touch those alluring arrow keys was pretty hard. There's a way to make it easier, and something I've seen in other peoples vimrc - just remap arrow keys to do absolutely nothing:

    noremap <Up> <Nop>
    noremap <Down> <Nop>
    noremap <Left> <Nop>
    noremap <Right> <Nop>

I found it very useful. But instead of just disabling, why not map arrow keys to do something useful? I currently have them mapped to text moving. In normal mode, arrows move current line in any direction. In visual mode, selected text gets moved. Let's start with moving text left and right in normal mode:

    nmap <Left> <<
    nmap <Right> >>

Not much to explain here. This maps your `Left` and `Right` keys to the same thing that `<<` and `>>` do. Which is - just move text to left or right. The same for visual mode looks a bit different:

    vmap <Left> <gv
    vmap <Right> >gv

In visual mode, selected areas get moved with `<` or `>`. There is one problem though. After area gets moved, it gets deselected. It's solved easily with `gv` command. It reselects the last visual area.
That takes care of moving text left and right. What about up and down?

    nmap <Up> [e
    nmap <Down> ]e
    vmap <Up> [egv
    vmap <Down> ]egv

[Tim Pope](//github.com/tpope), among a lot of other cool things, put together [unimpaired](//github.com/tpope/vim-unimpaired), which contains commands [\[e](//github.com/tpope/vim-unimpaired/blob/master/plugin/unimpaired.vim#L152) and [\]e](//github.com/tpope/vim-unimpaired/blob/master/plugin/unimpaired.vim#L153). They move text up and down - which fits perfectly here.

This is just one example you can map your arrows to. There are other alternatives. For example, navigating splits:

    nnoremap <Right> <C-w>l
    nnoremap <Left> <C-w>h
    nnoremap <Up> <C-w>k
    nnoremap <Down> <C-w>j

I just might remap `hjkl` to split navigation, because I use `hjkl` less and less, favoring navigating in other ways. Sounds crazy, I know ;)

You can check out my `vimfiles` on [GitHub](//www.github.com/mmozuras/vimfiles). Would love to hear your thoughts on arrows and `hjkl` usage in Vim.

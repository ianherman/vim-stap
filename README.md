# Introduction
SystemTap vim syntax highlighting scripts.
These scripts are copied by from the [official SytemTap repository][1]
to make it dotvim compatible.

# How to integrate into your own dotvim?

If you use Linux/MacOS X, try the following commands:
~~~~bash
cd ~/.vim
git submodule add https://github.com/schnell18/vim-stap bundle/vim-stap
git submodule update
git commit -m "Add vim script for SystemTap"
git push
~~~~

If you use Windows, try the following commands:
~~~~bash
cd c:\users\xxx\vimfiles
git submodule add https://github.com/schnell18/vim-stap bundle/vim-stap
git submodule update
git commit -m "Add vim script for SystemTap"
git push
~~~~

[1]: https://sourceware.org/git/gitweb.cgi?p=systemtap.git;a=tree;f=vim;hb=HEAD

Dane's Dotfiles
===============

What this is
------------
Based on Ryan Bates Dotfiles, added my own configs, and imported Janus.

Bpth dotfiles and Janus hav etheir own rake tasks for
installing/updating.


Install
-------

Clone, Run Rake Task for dotfiles, Run rake task for Janus

```
git clone https://github.com/danelowe/dotfiles.git ~/.dotfiles
cd ~/.dofiles
rake install
cd vim
rake
```

Add a Janus/Vim Plugin
----------------------

```
git submodule add https://github.com/terryma/vim-smooth-scroll.git janus/vim-smooth-scroll
```

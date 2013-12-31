Dirnavigate
===========

dirnavigate is a modified zsh theme of the original dircycle plugin from oh-my-zsh.
I created this plugin because i didn't like using popd and pushd to remember directories in a stack but instead just wanted to move forwards and backwards through directories.

Requirements
------------
- zsh (duhh)
- oh-my-zsh

Install
-------
cd /usr/share/oh-my-zsh/custom/plugin/
sudo git clone <git url>

then edit your .zshrc to add
plugins=(dirnavigate)

Controls
--------
Ctrl+Left   move back a directory
Ctrl+Right    move forward a directory

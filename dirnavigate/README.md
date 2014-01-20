----------------
WARNING: plugin does not seem to be working for me after reinstalling my os
tell me if it working for you
----------------

Dirnavigate
===========

dirnavigate is a modified zsh plugin originally from the dircycle plugin in oh-my-zsh.
I created this plugin because i didn't like using popd and pushd to remember directories in a stack but instead just wanted to move forwards and backwards through directories.

Requirements
------------
- zsh (duhh)
- oh-my-zsh

Install
-------
1. `git clone` this rep into a directory or just download a zip and extract into a folder
2. `sudo cp -r path-to-folder/dirnavigate /usr/share/oh-my-zsh/custom/plugin/dirnavigate`  
3. Then edit your .zshrc to add `plugins=(dirnavigate)`  
4. Finally restart your zsh shell.

Controls
--------
**Ctrl+Shift+Left**  <-  move back a directory  
**Ctrl+Shift+Right**  ->  move forward a directory

Screenshot
----------
![alt tag](sample.png)

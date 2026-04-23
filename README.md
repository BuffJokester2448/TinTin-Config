# TinTin-Config
Scripts made by Claude with minor edits done by me.
Made for LOTJ but structure is modular enough to work with any MUDS.

I have only tested the config on mobile.

## YOU NEED tintin++ INSTALLED IN YOUR TERMINAL FOR IT TO WORK!
### Edit private.tin for your characters
### Put ```alias LOTJ='cd ~/TinTin-Config/LOTJ && tt++ master.tin'``` (only if config is installed in root) in your .bashrc or .zshrc and run ```LOTJ``` to launch LOTJ.

## Android Steps
### Install Termux from F-DROID if you want to play it on mobile.

``pkg upgrade && pkg update``

``pkg install -y tintin++ git``

``git clone git@github.com:BuffJokester2448/TinTin-Config.git``

``nano ~/.bashrc`` (``nano ~/.zshrc`` if zsh) 

add ``alias LOTJ='cd ~/TinTin-Config/LOTJ && tt++ master.tin'`` at bottom of the line, ``CTRL+X, Y, ENTER`` to save it.

``LOTJ`` to run.

## Pinch in and Out in the Termux and Get Termux:Styling from F-DROID for further customization, just do a long tap on Terminal for customization options.

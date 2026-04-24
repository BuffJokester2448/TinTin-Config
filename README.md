# TinTin-Config
Scripts made by Claude with minor edits done by me.
Made for LOTJ but structure is modular enough to work with any MUDS.

I have only tested the config on mobile.

A lot of scripts are still WIP.

## YOU NEED tintin++ INSTALLED IN YOUR TERMINAL!
### Edit private.tin for your characters
### Aliases and scripts are saved in macros.tin and spacecombat.tin
### Put ```alias LOTJ='cd ~/TinTin-Config/LOTJ && tt++ master.tin'``` (only if config is installed in root) in your .bashrc or .zshrc and run ```LOTJ``` to launch LOTJ.

## Android Steps
### Install [Termux from F-DROID](https://f-droid.org/en/packages/com.termux/) or directly from [Github](https://github.com/termux/termux-app/releases) if you want to play it on mobile.

``pkg upgrade && pkg update``

``pkg install -y tintin++ git``

``git clone git@github.com:BuffJokester2448/TinTin-Config.git``

``nano ~/.bashrc`` (``nano ~/.zshrc`` if zsh) 

add ``alias LOTJ='cd ~/TinTin-Config/LOTJ && tt++ master.tin'`` at bottom of the line, ``CTRL+X, Y, ENTER`` to save it.

``source ~/.bashrc`` or ``source ~/.zshrc``

``LOTJ`` to run.

## Pinch in and Out in the Termux and Get [Termux:Styling from F-DROID](https://f-droid.org/en/packages/com.termux.styling/) or [Github](https://github.com/termux/termux-styling/releases) for further customization, just do a long tap on Terminal after installing it.

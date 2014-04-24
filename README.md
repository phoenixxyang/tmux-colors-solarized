# Solarize color theme tmux configuration

A tmux solarized theme using Ethan Schoonover’s [Solarized color scheme](http://ethanschoonover.com/solarized).

## NOTE
  * This fork is customized for my own using on Ubuntu 12.04.

## Repositories
  * This theme as a single repository: [/seebi/tmux-colors-solarized](https://github.com/seebi/tmux-colors-solarized)
  * The main solarized repository: [/altercation/solarized](https://github.com/altercation/solarized)

## Installation
These config snippets for the terminal multiplexer tmux should be added to your `~/.tmux.conf` configuration file.
This means you have to append the content of e.g. `tmuxcolors-256.conf` to the end of your own config e.g. by using this oneliner (backup you config first!!):

    cat tmuxcolors-256.conf >> ~/.tmux.conf
    cat dot_bashrc.append >> ~/.bashrc
    source ~/.bashrc

In most cases, you have to force tmux to assume the terminal supports 256 colours.
For this, start tmux as `tmux -2`. (See dot_bashrc.append, added this in bash alias)

This color scheme is tested with tmux >= 1.5. tmux 1.1 is reported as not working.

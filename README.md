# dot-tmux

My tmux dotfiles.

These are personalized for my own usage, but you can use them however you'd
like.

They're optimized for Vim users, and have lots of nice split window
functionality assigned to common Vim key mappings-- if you're a Vim user, it
should be intuitive.


## Installation

The below commands will download the project, and setup tmux.

```bash
sudo apt install tmux

mkdir -p ~/Drive/Sync/Dotfiles
git clone git@github.com:rdegges/dot-tmux.git ~/Drive/Sync/Dotfiles/tmux
ln -s ~/Drive/Sync/Dotfiles/tmux/tmux.conf ~/.tmux.conf
```


## Usage

To use tmux, run:

```bash
tmux
```

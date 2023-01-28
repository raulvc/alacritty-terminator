# alacritty (and tmux) with terminator shortcuts

For terminator users to migrate over to alacritty, which overperforms a billion times in comparison but has no pane splitting, therefore, we're using tmux.


Biggest motivation for this being tmux's default bindings which are *b a d*, like: [`ctrl + b` + `%`], [`ctrl + b` + `"`].


What I use:
- pane splitting
- pane maximizing
- scrolling
- renaming window title dynamically (though you'll need bash/zsh to do it for you, this only presents it)

## Config file locations
| app       |                                          |
|-----------|------------------------------------------|
| alacritty | ~/alacritty.yml, ~/.config/alacritty.yml |
| tmux      | ~/.tmux.config                           |

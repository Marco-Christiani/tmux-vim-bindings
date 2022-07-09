tmux-vim-bindings
=================
Forked from [0]

## Requirements

- [tmux][1]
- [TPM][2]

## Install

Add plugin to the list of [TPM][2] plugins in `.tmux.conf`:

```
set -g @plugin 'Marco-Christiani/tmux-vim-bindings'
```

`prefix + I` to fetch the plugin and source it.

## Bindings

### General

- `Alt+a` (`M-a`) - prefix, used to issue commands. Most of the commands are
  bound to `Alt` key directly (e.g. `Alt+num` to change windows instead of
  `Alt+a num`).
- `Alt+a d` - detach
- `Alt+q` - list key bindings (hotkeys)
- `Alt+c` - tmux new window
- `Alt+C` - tmux cmd prompt
- `Alt+m` - tmux man prompt
- `Alt+n` - tmux next window
- `Alt+p` - tmux prev window

Minor `tmux` key optimizations:

- `Alt+a a` (`M-a a`) - fast switching between alternate Windows
- `Alt+a r` (`M-a r`) - reload tmux configuration (source `~/.tmux.conf`)

### Sessions

- `Alt+e` (`M-e`) - list sessions

### Windows

- `Alt+t` (`M-t`) - new window
- `Alt+\`` (`M-\``) - toggle last window
- `Alt+NUM`(`M-NUM`) - select window NUM (1-9)
- `Alt+s` (`M-s`) - split window horizontally
- `Alt+v` (`M-v`) - split window vertically
- `Alt+w` (`M-w`) - close window

### Panes

- `Alt+Tab` (`M-Tab`) - toggle last pane
- `Alt+h/l/j/k` (`M-h/l/j/k`)  - pane selection (hljk)
- `Alt+Shift+h/l/j/k` (`M-H/L/J/K`) - pane resize
- `Alt+d` (`M-d`) - swap pane forward
- `Alt+Shift+d` (`M-D`) - swap pane backward
- `Alt+w` (`M-w`) - close pane

## Authors

[ek9](https://github.com/ek9/)
[Me](https://github.com/Marco-Christiani/)

## License

Licensed under [MIT License](LICENSE).

[0]: https://github.com/ek9/tmux-vim-bindings
[1]: https://github.com/tmux/tmux
[2]: https://github.com/tmux-plugins/tpm

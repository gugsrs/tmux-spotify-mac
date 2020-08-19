# tmux-spotify-mac

Show current spotify track artist and name on tmux status bar.

## Instalation
### Using Tmux Plugin Manager

Add plugin to the list of plugins at the end of `tmux.conf`:
```
set -g @plugin 'gugsrs/spotify-info-mac'
```

## Usage
```
set -g status-right "#{spotify-info}"
```

## License
MIT
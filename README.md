# LS_COLORS yazi-theme

[LS_COLORS by trapd00r](https://github.com/trapd00r/LS_COLORS) contains unique colors from over 300 different file types. This is typically used by ls (or ls-like commands like [lsd](https://github.com/lsd-rs/lsd)) to color files in the terminal.

This repository contains a yazi theme that uses the colors from LS_COLORS. The colors were converted using [lsColorsToToml](https://github.com/Mellbourn/lsColorsToToml)

## Install

```sh
git clone https://github.com/Mellbourn/ls-colors-yazi-theme
mkdir ~/.config/yazi
cd ls-colors-yazi-theme
mv theme.toml ~/.config/yazi/
```

Screenshot in tmux showing yazi in the top pane and an [lsd](https://github.com/lsd-rs/lsd) list below. Notice that the colors match.
![Terminal screenshot](./Screenshot.png)

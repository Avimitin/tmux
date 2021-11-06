# tmux

*Default theme*
![screenshot](./tmux-screenshot.png)

*Nord theme*
![screenshot](./tmux-nord.png)

## Install

First of all, you need a nerd font for icons:
[nerd font](https://nerdfonts.com/)

Then clone the repo and copy the config file to your home path.

```bash
git clone https://github.com/Avimitin/tmux
cp tmux/.tmux.conf ~/
# if you want the Nord Theme
cp tmux/.tmux.conf.nord ~/.tmux.conf
```

## Keys

```text
* prefix:                <Ctrl-a>
* next window:           <Ctrl-Right>
* previous window:       <Ctrl-Left>
* move next:             <prefix>l
* move previous:         <prefix>h
* move up:               <prefix>k
* move down:             <prefix>j
* new session:           <prefix><Ctrl-c>
* split horizontal pane: <prefix>_
* split vertical pane:   <prefix>-
* toggle mouse:          <prefix>m
* copy mode:             <prefix>Enter
```

## Credit

Keymap is copied from
[gpakosz/.tmux](https://github.com/gpakosz/.tmux).

Some setting is copied from
[reorx/dotfiles](https://github.com/reorx/dotfiles/blob/master/tmux.conf).

Colorscheme is inspired by
[wfxr/tmux-power](https://github.com/wfxr/tmux-power).

## License

MIT License

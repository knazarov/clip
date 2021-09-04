# Copy text to clipboard from shell

This script uses OSC52 escape sequences to copy text to clipboard,
which means you can do it even when working through SSH.

Supports:

* Plain shell
* GNU screen
* tmux

Note, that you need a terminal that understands the OSC52 escape sequence.
Regular MacOS terminal doesn't, so you'll need iterm2, kitty, alacritty
or any other modern 3-rd party terminal.

On Linux, you'll need something different from gnome-terminal or konsole.
Again, alartitty will be a good option.

## Usage

```sh
echo -n "copyme" | ./clip
```

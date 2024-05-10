# dmenu

Extra stuff added to vanilla dmenu:

- reads Xresources (pywal compatible)
- alpha patch, which importantly allows this build to be embedded in transparent st
- can view color characters like emoji (libxft is required for this reason)
- `-P` for password mode: hide user input
- `-r` to reject non-matching input
- dmenu options are mouse clickable

## Installation
You should aready have all dependencies met after installed graphical desktop apps like mpv. \
Install libxft if you want to show emoji in dmenu.

fonts: [firacode nerd(modified)](https://github.com/0n3W4y7ick3t/deployLinux/tree/main/firacode-nerd) and noto-emoji

Run `sudo make install` to make and install dmenu.

- Use dmenu_run to call it instead of dmenu.

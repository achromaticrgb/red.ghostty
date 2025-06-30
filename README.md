# red.ghostty

Achromatic colorscheme with red accent, perfect for LED screens.

# Installation

Copy/Download `red` into `/usr/share/ghostty/themes` and add `theme = red` into `~/.config/ghosty/config`

```sh
cd /usr/share/ghostty/themes && \
sudo curl -O \
https://raw.githubusercontent.com/achromaticrgb/red.ghostty/refs/heads/main/red && \
mkdir -p $HOME/.config/ghostty && \
touch $HOME/.config/ghostty/config && \
echo "theme = red" >> $HOME/.config/ghostty/config
```

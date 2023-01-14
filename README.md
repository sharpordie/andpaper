# <samp>OVERVIEW</samp>

Unofficial wallpapers for any Android enthusiasts.

## Bottom variant

<a href="src/android-bottom-bright.png"><img src="src/android-bottom-bright.svg" width="49.5%"/></a><a><img src="assets/none.png" width="1%"/></a><a href="src/android-bottom-darken.png"><img src="src/android-bottom-darken.svg" width="49.5%"/></a>

## Higher variant

<a href="src/android-higher-bright.png"><img src="src/android-higher-bright.svg" width="49.5%"/></a><a><img src="assets/none.png" width="1%"/></a><a href="src/android-higher-darken.png"><img src="src/android-higher-darken.svg" width="49.5%"/></a>

## Middle variant

<a href="src/android-middle-bright.png"><img src="src/android-middle-bright.svg" width="49.5%"/></a><a><img src="assets/none.png" width="1%"/></a><a href="src/android-middle-darken.png"><img src="src/android-middle-darken.svg" width="49.5%"/></a>

# <samp>GUIDANCE</damp>

## Set wallpaper on macOS

```shell
address="https://github.com/sharpordie/andpaper/raw/main/src/android-bottom-bright.png"
picture="$HOME/Pictures/Backgrounds/$(basename "$address")"
mkdir -p "$(dirname $picture)" && curl -Ls "$address" -o "$picture"
osascript -e "tell application \"System Events\" to tell every desktop to set picture to \"$picture\""
```

## Set wallpaper on Ubuntu

```shell
address="https://github.com/sharpordie/andpaper/raw/main/src/android-bottom-bright.png"
picture="$HOME/Pictures/Backgrounds/$(basename "$address")"
mkdir -p "$(dirname $picture)" && curl -Ls "$address" -o "$picture"
gsettings set org.gnome.desktop.background picture-uri "file://$picture"
gsettings set org.gnome.desktop.background picture-options "zoom"
gsettings set org.gnome.desktop.screensaver picture-uri "file://$picture"
gsettings set org.gnome.desktop.screensaver picture-options "zoom"
```

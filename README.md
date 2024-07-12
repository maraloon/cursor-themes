# Gruvebox and Groovebox cursor themes
Themes generated via [ful1e5/Google_Cursor](https://github.com/ful1e5/Google_Cursor) 

Just paste them to `~/.local/share/icons` and sway config:
```
set $cursor-theme GoogleDot-Groovebox
set $cursor-size 32
seat * hide_cursor 2000
seat * xcursor_theme $cursor-theme $cursor-size
exec gsettings set org.gnome.desktop.interface cursor-theme $cursor-theme
exec gsettings set org.gnome.desktop.interface cursor-size $cursor-size
```

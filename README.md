# GtkSourceView-Snort
This package provides Snort and Suricata IDS rule syntax highlighting for Gtk-based text editors such as gedit and [xed](https://github.com/linuxmint/xed)

#### To install:
Save `snort-suricata.lang` to the user's `language-specs` dir (see https://developer.gnome.org/gtksourceview/stable/lang-reference.html):

```sh
mkdir -pv ~/.local/share/gtksourceview-3.0/language-specs/
cp ./snort-suricata.lang ~/.local/share/gtksourceview-3.0/language-specs/
```

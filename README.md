# NeonFvwmGtk

NeonFvwmGtk is a fork of [Diehard4](https://github.com/tacojones/Diehard4),
you can found the icon theme [here](https://github.com/Manu-sh/NeonFvwmIconTheme)

![screenshot](https://anonimag.es/i/22_02_2017-155501_xorg902fa.png)

###Installation
```bash

# clone
git clone https://github.com/Manu-sh/NeonFvwmGtkTheme

cd NeonFvwmGtkTheme

sudo cp -R NeonFvwmGtk /usr/share/themes
```

### Configuration
for setting a theme as default there are two common way

* one way is using theme manager
* another way is using the [default files readed by gtk](https://wiki.archlinux.org/index.php/GTK%2B)

an example of .gtkrc-2.0 file

```
gtk-icon-theme-name = "NeonFvwmIcon"
gtk-theme-name = "NeonFvwmGtk"
gtk-font-name = "Terminus 8"
```

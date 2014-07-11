font_configuration
==================

My Debian font configuration.

## Install

```
aptitude install fonts-droid fonts-liberation fonts-wqy-microhei fonts-arphic-uming
```

## configure
copy fonts.conf to ~/.config/fontconfig/fonts.conf

if you have X client applications (xterm, rxvt, etc), copy Xresources to ~/.Xresources, and then:

```
$ xrdb -merge ~/.Xresources
```

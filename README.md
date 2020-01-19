# GRUB2 Theme Waft

## Installation

1. Clone git repository

```
https://github.com/totoroot/grub2-waft.git
```

2. Copy the whole directory with root privileges

```
sudo cp -r grub2-waft /boot/grub/themes
```

3. Add line GRUB_THEME to grub

```
sudo nano /etc/default/grub
```

```
GRUB_THEME="/boot/grub/themes/grub2-waft/theme.txt"
```

4. Update grub

```
grub-mkconfig -o /boot/grub/grub.cfg

```

## Background Image

Photo by Vidar Nordli-Mathisen on Unsplash:
https://unsplash.com/@vidarnm

Download for free from:
https://unsplash.com/photos/K4c8RymNeu8

Change it easily by putting your own image into directory and renaming it to "theme.png".

## Font License

Open Sans by Google

Released under:
Apache License
Version 2.0, January 2004

https://www.apache.org/licenses/

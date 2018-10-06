## GRUB2 Theme Waft

# Installation


* 1. Clone or download and extract git repository

* 2. Copy the whole directory with root privileges

sudo cp -r waft /boot/grub/themes

* 3. Add line GRUB_THEME to grub

sudo nano /etc/default/grub

```
GRUB_THEME="/boot/grub/themes/waft/theme.txt"
```

* 4. Update grub

```bash
$ grub-mkconfig -o /boot/grub/grub.cfg

```

# Background Image

* Photo by Vidar Nordli-Mathisen on Unsplash:
* https://unsplash.com/@vidarnm

* Download for free from:
* https://unsplash.com/photos/K4c8RymNeu8

* change it easily by putting your own image into directory and
* rename it to "theme.png"

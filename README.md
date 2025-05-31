
# Terragrub

A Terraria theme for GRUB and nothing else.
I'll be updating this theme as I can to fix some issues until it's finished.

## Disclaimer
First of all, thanks to Lxtharia for the [Minegrub theme](https://github.com/Lxtharia/minegrub-theme). I used this theme as an inspiration. I really enjoyed this theme and I wanted to give some credit for it.

Secondly, Terragrub was made just for my needs.
Terraria is one of my favorite games of all time, so I looked for a GRUB theme or something closer, but I did not find anything, so I made my own theme.

## Installation

Go to your files and find the external directory of this project and copy its content to:
```
sudo cp -ruv ./terragrub /boot/grub/themes/
```

Open */etc/default/grub* with your text editor, e.g.:

```
sudo nano /etc/default/grub
```

And add or change this line

```
GRUB_THEME=/boot/grub/themes/terragrub/theme.txt
```

And finally, update your GRUB configuration:
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

or just do (easy to remember, but maybe it won't work on some Linux distributions)

```
sudo update-grub
```

And there you go. You should have a functional GRUB Terraria theme.

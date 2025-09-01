# omarchy

<pre class="pre">
                 ▄▄▄
 ▄█████▄    ▄███████████▄    ▄███████   ▄███████   ▄███████   ▄█   █▄    ▄█   █▄
███   ███  ███   ███   ███  ███   ███  ███   ███  ███   ███  ███   ███  ███   ███
███   ███  ███   ███   ███  ███   ███  ███   ███  ███   █▀   ███   ███  ███   ███
███   ███  ███   ███   ███ ▄███▄▄▄███ ▄███▄▄▄██▀  ███       ▄███▄▄▄███▄ ███▄▄▄███
███   ███  ███   ███   ███ ▀███▀▀▀███ ▀███▀▀▀▀    ███      ▀▀███▀▀▀███  ▀▀▀▀▀▀███
███   ███  ███   ███   ███  ███   ███ ██████████  ███   █▄   ███   ███  ▄██   ███
███   ███  ███   ███   ███  ███   ███  ███   ███  ███   ███  ███   ███  ███   ███
 ▀█████▀    ▀█   ███   █▀   ███   █▀   ███   ███  ███████▀   ███   █▀    ▀█████▀
                                       ███   █▀
</pre>

My [Omarchy](https://omarchy.org) config.

## Installation

``` sh 
stow -S pkg -t ~/
```

# Features

## Web Apps

- Amazon Prime Video
- Gitea
- Logos
- Netflix
- Plex

## Hyprland

## Waybar

## Scripts

Linux/LVFS
Updating via LVFS is available in the stable channel. You can enable updates from testing by running;

fwupdmgr refresh --force

then



fwupdmgr get-updates


then



fwupdmgr update



LVFS may not update if the battery is 100% charged. LVFS uses the battery status to determine if it is safe to apply updates. However if our battery is at 100% and the charger is off, we set the battery charging status to false. In this case you can discharge your battery a few percent, then plug in AC again and run fwupdmgr update.

You can see the current releases status at 

https://fwupd.org/lvfs/devices/work.frame.Laptop16.Ryzen7040.BIOS.firmware 





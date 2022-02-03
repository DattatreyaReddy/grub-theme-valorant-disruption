# valorant-disruption
## valorant-disruption is a grub theme
- Copy this repo to `/usr/share/grub/themes/`
- edit ` /etc/default/grub ` file
    - `nano  /etc/default/grub `
- Change the value of the var `GRUB_THEME` to `"/usr/share/grub/themes/grub-theme-valorant-disruption/theme.txt"` 
    - ```GRUB_THEME="/usr/share/grub/themes/grub-theme-valorant-disruption/theme.txt"```
- now execute `sudo update-grub` to install this theme

## Preview
![Valorant-disruption-grub-preview](grub_preview.png)

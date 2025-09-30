# ARCH LINUX RICE 🍚 ⋆˙⟡
> ~~This is currently still a working progress. More updates to come as I adjust and add more to my rice.~~



### Arch Packages used:
```
yay -S hyprland waybar swww wofi
```

# WAYBAR

### Credits:
> Inspired by:
[Bruno Anesio's Waybar](https://github.com/brunoanesio/waybar-config)
And Also Using Caway: 
[PROxZIMA's Caway](https://github.com/PROxZIMA/caway)

![waybar screenshot](https://github.com/faithfel/rice-rice-baby/blob/main/screenshots/waybar%20screenshot.png)



# HYPRLAND
### Hyprland Installation:

```
sudo pacman -S hyprland
```
### Keybinds:
My Super Key has been changed to ALT

| Action        |  Key Binds    |
| ------------- | ------------- |
| ALT Q         |     Terminal  |
| ALT X         |   Kill Active |
| ALT 0         |  Exit Hyprland|
| ALT W         |   File Manager|
| ALT F         |Toggle Floating|
| ALT M         |      Menu     |
| ALT J         |  Toggle Split |

## Additional KeyBinds
Hyprshot with Grimblast for screenshots

Installation:
```
yay -S hyprshot
yay -S grimblast
```
| Action        |  Key Binds    |
| ------------- | ------------- |
| ALT I         |Capture area to clipboard |
| ALT K         |Save area to clipboard |
| ALT O         |Capture full output to clipboard |
| ALT P         |Save full output to file|


### Autostart in Hyprland:
```
exec-once = waybar
```

# Troubleshooting

- [Waybar Clock Incorrect or only showing UTC time](https://bbs.archlinux.org/viewtopic.php?id=299285)

# Potential_bar
![image](https://user-images.githubusercontent.com/96730056/153717555-c8f51729-7206-4d22-8233-b42881ef9290.png)

#### Beautiful , fast , simple bar for dwm with multiple themes
* gruvchad
* nord
* onedark
* samir

## Feature :smile:
### dwm_spotify
Displays what is playing in spotify
 ```
Eminem - Lose Yourself 3:12
```
### battery
Displays battery level and colour change according to charge percentage and charging status
 ```
🔋
```
### Brightness
Displays the brigntness percentage
```
☀️
```

### Cpu usage
Show the cpu usuage

```
💻
```
### mem
Displays the ram usuage
```
⌨
```

### clock
show date and time in beautiful way
```
```
## Dependency
 #### acpi
```
yay -S acpi
```
 #### Light
 light
 ```
 yay -S light
 ```

 #### Spotifyd
 ```
 yay -S spotifyd
 ```


## How to install and use

* First clone the repro:
  ```
  git clone https://github.com/PotentialAlu/potential_bar
* Second allow everyone to execute the script

   ```
    chmod +x bar.sh
* Execute the script on startup via .xinirc

   open .xinitrc file which is located on ~/.xinitrc and add the following line in the file
 `Note:` My script is on ~/.dwm/potential_bar/bar.sh you are supposed to change this according to where you  have installed the script
```
  sh ~/.dwm/potential_bar/bar.sh
```

## How to change themes
change  this line in bar.sh file according to your choice

`. ~/.dwm/bar/themes/samir`

### Fell free to report if something isn,t working properly



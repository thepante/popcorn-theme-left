![Screenshot](https://i.imgur.com/8iwlWiY.png)
## Modernleft theme
Theme with small modifications for Popcorn Time that moves the window buttons to the left, mainly. Made and tested only on Linux. Should be good on Windows too.

## What's different  
 -  Window buttons moved to the left
 -  Hide `fullscreen` button (I use `ctr+alt+f`)
 -  Dim toolbar, when hover slightly ups opacity
 -  Dimmed right toolbar buttons

## Install it  
Manually, using mouse:  
 1.  Download this repo as `.zip`
 2.  Extract the `.css` file
 3.  Paste it, inside of your _folder of Popcorntime_`/src/app/themes`
 4.  Select it on the Settings menu
 
**OR** From terminal, assuming your app path is `/opt/popcorntime`, one line:
```bash
wget https://github.com/thepante/popcorn-theme-left/archive/master.zip && unzip master.zip && mv popcorn-theme-left-master/Official_-_Dark_-_Modernleft_theme.css /opt/popcorntime/src/app/themes/Official_-_Dark_-_Modernleft_theme.css && rm -r popcorn-theme-left-master && rm master.zip
```

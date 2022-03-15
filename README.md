# My simple dwm setup

## Installed patch 

- [Always center](https://dwm.suckless.org/patches/alwayscenter/dwm-alwayscenter-20200625-f04cac6.diff)
- [Move Stack](https://dwm.suckless.org/patches/movestack/dwm-movestack-6.1.diff)
- [Status all monitor](https://dwm.suckless.org/patches/statusallmons/dwm-statusallmons-6.2.diffhttps://dwm.suckless.org/patches/statusallmons/dwm-statusallmons-6.2.diff)

## Install 

```bash
git clone git@github.com:fadzrilizad/dwm.git
cd dwm 
make clean 
make && sudo make clean install
```

## Note
 
|modfiers                     |function                             |
|-----------------------------|-------------------------------------|
|alt                          |modkey                               |
|alt+shift+enter              |open terminal                        |
|alt+p                        |open dmenu                           |
|alt+shift+q                  |quit window                          |
|alt+shift+r                  |restart dwm                          | 
|alt+number                   |go to workspace number               | 
|alt+shift+number             |move window to workspace number      |
|alt+l                        |resize window to the right           |
|alt+h                        |resize window to the left            |
|alt+j / k                    |move between window j=up k=down      |
|alt+shift j / k              |change window location               | 
|ctrl+shift+pageUp / pageDown |zoom terminal                        | 
|alt+space                    |toggle floating window               |
|alt+b                        |toggle bar                           |
|alt+tab                      |change active workspace              |
|alt+shift+space              |change current window to floating    |
|alt+i                        |increase stact (horizontal view)     |
|alt+d                        |decrease stact (vertical view)       |
|alt+m                        |make all window fullscreen           |
|alt+f                        |next window will be floating         |
|alt+t                        |make fullscreen / floating normal    |
|alt+0                        |view current window in all workspace |
|alt+shift+0                  |open current in all workspace        |


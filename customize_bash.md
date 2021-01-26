# The same colour of background in bash linux, following the next steps
```
sudo apt update && sudo apt upgrade 
sudo apt install imagemagick 
sudo apt install python3-pip
sudo apt pip3 install pywal
```
# Is necessary to setting the bash and put the path direction  of image background
```
gsettings get org.gnome.desktop.background picture-uri
nano .bashrc
```
# Code inside of the bash linux 
```
wallpaper=$(gsettings get org.gnome.desktop.background picture-uri)
wallpaper=${wallpaper/file:\/\//""}
wallpaper=${wallpaper//\'/""}
wal -n -q -i "$wallpaper"
``



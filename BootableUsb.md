# Bootable usb on ubuntu 

## 1. Clean your usb with GPaterd
```
sudo apt-get install gparted
```
## 2. Install bootiso
```
curl -L https://git.io/bootiso -O
chmod +x bootiso
sudo apt install wimtools 
sudo apt install syslinux 
sudo apt install extlinux 
```
## 3. Example 
```
./bootiso /home/antony/Descargas/pop-os_20.04_amd64_intel_18.iso 
```
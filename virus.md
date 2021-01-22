# Detecting and Clearing virus on Ubuntu 
## Installing software

```
sudo apt-get install clamav clamav-daemon -y
sudo freshclam
```

## Searching virus 

```
sudo clamscan -r /home/barja/Descargas/
```

## Remove virus 

```
sudo clamscan --infected  --remove -recursive /home/barja/Descargas/
```

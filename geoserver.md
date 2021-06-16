## Install Java

```
sudo apt-get install openjdk-8-jdk
sudo apt-get install openjdk-8-jre
java -version
```

## Install Geoserver 
```
cd /usr/share
mkdir geoserver
cd geoserver
wget https://sourceforge.net/projects/geoserver/files/GeoServer/2.18.1/geoserver-2.18.1-bin.zip
unzip geoserver-2.18.1-bin.zip
rm geoserver-2.18.1-bin.zip
```
## Configuration of user 

```
echo “export GEOSERVER_HOME=/usr/share/geoserver”
sudo "chown -R USER_NAME /usr/share/geoserver/"
cd /usr/share/geoserver/bin
sh startup.sh
http://localhost:8080/geoserver/
```
#### Reference:
* https://www.igismap.com/install-geoserver-ubuntu/
* https://medium.com/random-gis-talks/installing-geoserver-binary%EF%B8%8F-on-ubuntu-18-04-using-terminal-ff9429ab47fa

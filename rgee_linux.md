# Installing dependences of rgee library
```
sudo apt install  libjq-dev
sudo apt install libprotobuf-dev
sudo apt install protobuf-compiler
```
```
install.packages('rgee',dep = T)
install.packages('geojsonio',dep = T)
library(rgee)
ee_install()
ee_Initialize('email',drive = TRUE, gcs = 'put__if_you_have_a_count_of_google_cloud_storage')

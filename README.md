# ydlidar
ydlidarのsdk確保やプログラム置き場
## build
下記のバージョンをダウンロードして使うとこけない
https://www.ydlidar.com/service_support/download.html?gid=22

この時のバージョンは1.1.2
``` 
$ cd YDLidar-SDK/build
$ cmake ..
$ make
$ sudo make install
```

## pythonで利用
``` 
$ sudo apt-get update && sudo apt-get install -y swig
$ cd YDLidar-SDK/build
$ sudo apt-get install python3-pip
$ pip3 install .
``` 

RPi5(Bookworm)、JetsonOrinNano(Ubuntu22)で確認済み。



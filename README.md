# InsecureBankv2-docker

This project is none other than the InsecureBankV2 application available at this url: https://github.com/dineshshetty/Android-InsecureBankv2. This is just a port of the server written in python2 on docker.

## Installation / Configuration
1) Download this project.
```
git clone https://github.com/CobblePot59/InsecureBankv2-docker.git
```
2) Launch docker-compose to start the server.
```
docker compose up -d --build
```
3) Install the app on the Android KitKat device.
```
adb install InsecureBankv2.apk
```
4) Open InsecureBankv2 and configure it with server ip
<img src="https://raw.githubusercontent.com/CobblePot59/InsecureBankv2-docker/main/pictures/server.png" width="200" height="400">
5) Login and have a fun ;)
<img src="https://raw.githubusercontent.com/CobblePot59/InsecureBankv2-docker/main/pictures/login.png" width="200" height="400">

__Remarque :__ The credentials are dinesh/Dinesh@123$ or jack/Jack@123$

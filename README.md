## SLxray Script 

------------------------------------------
## : No domain script : Installation - Without DNS

* Ubuntu 20.04 or Ubuntu-latest Os එක සහිත Vps එකක්.
* UUID එකක් (V2rayN මගින් හෝ http://uuidgenerator.net මගින් UUID එකක් Genarate කරගන්න).

1) first command 
```
apt-get update -y && apt-get upgrade -y && apt install git -y && apt install vnstat -y && sudo reboot  
```

2) second command
```
sudo git clone https://github.com/Slehibot/SLxray && cd SLxray && sudo chmod 777 xray-nodomain.sh && sudo ./xray-nodomain.sh  
```
* 80 : vmess+tcp+http
* 8443 : vless+tcp+xtls  

Sample Configuration : vmess Non TLS 80
```
vmess://eyJhZGQiOiIxNzIuMTA1LjEyNS45MyIsImFpZCI6IjAiLCJob3N0IjoibS5mYWNlYm9vay5jb20iLCJpZCI6IjU2NDA0NzliLWJmNTEtNGRiZC1hNWI4LTg2Y2FjOTUwMDBhOSIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwicG9ydCI6IjgwIiwicHMiOiJMYWttYWxfU0dfWHJheV8iLCJzY3kiOiJhdXRvIiwic25pIjoiIiwidGxzIjoiIiwidHlwZSI6Imh0dHAiLCJ2IjoiMiJ9 
```
Sample Configuration : vless TLS 8443 
```
vless://5640479b-bf51-4dbd-a5b8-86cac95000a9@172.105.125.93:8443?security=xtls&encryption=none&headerType=none&type=tcp&flow=xtls-rprx-splice&sni=www.facebook.com#Lakmal_SG_Xray_ 
```

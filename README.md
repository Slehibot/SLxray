------------------------------------------
## : No domain script : Installation - Without DNS

1) first command 
```
apt-get update -y && apt-get upgrade -y && apt install git -y && apt install vnstat -y && sudo reboot  
```

2) second command
```
sudo git clone https://github.com/Slehibot/SLxray && cd bash-xray-script && sudo chmod 777 xray-nodomain.sh && sudo ./xray-nodomain.sh  
```
* 80 : vmess+tcp+http
* 8443 : vless+tcp+xtls  


1) sudo rm  -rf  ~/bash-xray-script

2) sudo git clone https://github.com/Slehibot/bash-xray-script

3) cd bash-xray-script

4) sudo chmod 777 remove-xray.sh

5) sudo ./remove-xray.sh

## :octocat: Credits

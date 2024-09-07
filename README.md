 <p align="center">


<h2 align="center">
Auto Script Install XRAY/SSH Websocket Service
Mod By NevermoreSSH
<img src="https://img.shields.io/badge/Release-v3.0-red.svg"></h2>

</p> 
<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"width="400"></p> 
<p align="center">
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> 
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2011&message=bullseye&color=purple"> 
<p align="center">
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=ubuntu%2018.04 LTS&message=Bionic Beaver&color=red"> 
<img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=ubuntu%2020.04 LTS&message=Focal Fossa&color=red"> 
</p>



<h2 align="center">Network VPN</h2>

<h2 align="center">

![Hits](https://img.shields.io/badge/SSH-Websocket-8020f3?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/XRAY-Vmess-f34b20?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/XRAY-VLess-f34b20?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
![Hits](https://img.shields.io/badge/XRAY-Trojan-f34b20?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)
</h2>

PLEASE MAKE SURE YOUR DOMAIN SETTINGS IN YOUR CLOUDFLARE AS BELOW (SSL/TLS SETTINGS)<br>
<br>

1. Your SSL/TLS encryption mode is Full
2. Enable SSL/TLS Recommender ✅
3. Edge Certificates > Disable Always Use HTTPS (off)

<br>
♦️ For Debian 9 / 10 / 11 For First Time Installation (Update Repo) <br>
 
  ```html
 apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
  ```
  ♦️ For Ubuntu 18.04 / 20.04 For First Time Installation (Update Repo) <br>
  
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```
♦️ Installation Link <br>

  ```html
apt --fix-missing update && apt update && apt upgrade -y && apt install -y bzip2 gzip coreutils screen dpkg wget vim curl nano zip unzip && wget -q https://raw.githubusercontent.com/Sanjays85141/BlueSSHWS/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
  ```
IPV6 enable
```html
apt --fix-missing update && apt update && apt upgrade -y && apt install -y bzip2 gzip coreutils screen dpkg wget vim curl nano zip unzip && wget -q https://raw.githubusercontent.com/Sanjays85141/BlueSSHWS/main/setup2.sh && chmod +x setup2.sh && screen -S setup ./setup2.sh
  ```
<b>

[ SERVICES ] <br>
<br>
✅ SSH WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY VMESS WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY VLESS WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY TROJAN WEBSOCKET TLS & NON-TLS 443/80<br>
<br>

[ OTHER SERVICES ] <br>
<br>
✅ NEW UPDATE BBRPLUS 5.15.96 <br>
✅ BANDWITH MONITOR <br>
✅ RAM MONITOR <br>
✅ DNS CHANGER <br>
✅ NETFLIX REGION CHECKER <br>
✅ CHECK LOGIN USER <br>
✅ CHECK CREATED CONFIG <br>
✅ AUTOMATIC CLEAR LOG <br>
✅ AUTOMATIC VPS REBOOT <br>
✅ BACKUP & RESTORE <br>
✅ XRAYCORE CHANGER <br>
✅ VIRTUAL SWAPRAM <br></br>


```
   [ Service & Port ]
   - OpenSSH                 : 22
   - SSH Websocket           : 80
   - SSH SSL Websocket       : 443
   - Stunnel5                : 447, 777
   - Dropbear                : 109, 143
   - Badvpn                  : 7100-7300
   - Nginx                   : 81
   - XRAY Vmess GRPC         : 443
   - XRAY Vmess TLS          : 443
   - XRAY Vmess None TLS     : 80
   - XRAY Vless GRPC         : 443
   - XRAY Vless TLS          : 443
   - XRAY Vless None TLS     : 80
   - XRAY Trojan GRPC        : 443
   - XRAY Trojan GO          : 443
   - XRAY Trojan WS          : 443
   - Sodosok WS/GRPC         : 443

   [ Server Information & Other Features ]
   - Timezone                : Asia/Kuala_Lumpur (GMT +8)
   - Fail2Ban                : [ON]
   - Dflate                  : [ON]
   - IPtables                : [ON]
   - Auto-Reboot             : [ON] - 5.00 AM
   - IPv6                    : [OFF/ON]
   - Autoreboot Off          : [ON]
   - Autobackup Data         : [OFF]
   - AutoKill Multi Login User
   - Auto Delete Expired Account
   - Fully automatic script
   - VPS settings
   - Admin Control
   - Restore Data
   - Full Orders For Various Services
```

# Aura-Proxy
A High End Proxy Made by me



HOW TO USE


How to setup:

U need ubuntu 24.04

Run Theas commands below

apt update && apt upgrade -y
apt install screen -y

cd proxy

leave the listen_address in line 2 to 0.0.0.0 for the default address of your proxy server, and change the number behind the : it will be the port to connect! 

change line 3 the target_address with your backend ip:port for example ->  8.8.8.8:22

chmod 777 aura-proxy

sudo screen ./aura-proxy


line 9-13 is for ur discord webhook to get notifyed when someone connects



MADE BY TOM THE CAT aka tomsek.exe

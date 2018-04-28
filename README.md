# Sci Chicken

A PUBG pcap playback system that does not hog CPU/GPU, works with version 3.7.33

## Sniff

You need an extra linux（centos 7 x64） server to be the man in the middle

Server running command：
```bash
yum install git;git clone https://github.com/794959818/PUBG-Radar-Onekey.git; chmod +x . /root/PUBG-Radar-Onekey/update.sh;. /root/PUBG-Radar-Onekey/update.sh
```

## Translation

回车后开始安装  Enter after installation

记住了吗？任意键继续  Remember? Any key continues

请输入你的内网ip   Please enter your private Network ip

搭建完成 Build up


## Link

Local computer using SSTAP connection

Watching address  serverIP:20086/


Restart PUBG-Radar command

```bash
cd /root/PUBG-Radar-Onekey;. restart.sh

SSTap 百度自己下载  Xshell_5 百度自己下载



搭建加速器

wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh

chmod +x shadowsocks-all.sh

./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log


设置SSTap进行加速

安装nodejs和npm
curl https://raw.githubusercontent.com/creationix/nvm/v0.13.1/install.sh | bash

source ~/.bash_profile

nvm install v9.8.0

nvm alias default v9.8.0

安装libpcap
yum -y install gcc-c++

yum -y install flex

yum -y install bison

wget http://www.tcpdump.org/release/libpcap-1.8.1.tar.gz

tar -zxvf libpcap-1.8.1.tar.gz

cd libpcap-1.8.1

./configure

make

make install
安装部署项目
yum install git

git clone https://github.com/794959818/PUBG-Radar-Onekey

cd PUBG-Radar-Onekey/

npm i

npm i -g pino

npm install -g forever
 
forever start index.js sniff eth0 172.xx.xx.xx | pino


一键方法
4.27公告，目前雷达正常有小bug，推荐阿里云
yum install git;git clone https://github.com/794959818/PUBG-Radar-Onekey.git;chmod +x . /root/PUBG-Radar-Onekey/update.sh;. /root/PUBG-Radar-Onekey/update.sh
正式版一键安装命令
雷达网页打不开，不跟踪，运行此命令
cd /root/PUBG-Radar-Onekey;. restart.sh
正式版


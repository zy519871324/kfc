



20180429更新复制了kfc的部分代码    下一步JS本地化




-------------------------------------------------------------------------------------------------------------------------------

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


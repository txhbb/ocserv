# ocserv
Cisco anyconnect Server config &amp; install</br>
思科anyconnect服务器搭建& windows、osx、iphone、安卓不同系统客户端连接教程
本教程：通过一个脚本文件快速搭建自己的VPN服务器（anyconnect），支持windows、苹果、iphone、android、linux等不同操作系统
1、脚本文件
-----------------------------------------------------------------------------------------
sudo -i 
yum install wget -y 
wget https://raw.githubusercontent.com/che... 
chmod +x install_script.sh 
./install_script.sh
---------------------------------------------------------------------------------------------------------

2 、新建或删除账号的方法
------------------------------------------------------------------------------------------------------------
cd /root/anyconnect/
/root/anyconnect/user_add.sh
输入用户名和密码即可创建账号
删除账号的方法
cd /root/anyconnect/
/root/anyconnect/user_del.sh
输入要删除的账号
-----------------------------------------------------------------------------------------------------------

3、客户端下载地址
#Anyconnect Client for windows system
http://180.188.197.212/down/anyconnec...
#Anyconnect Client for osx
http://180.188.197.212/down/anyconnec...
#Anyconnect Client for andriod
http://180.188.197.212/down/anyconnec...

本VPN服务器的特点包括：安装方便，一键脚本，可以供多人使用，协议采用cisco anyconnect 不容易被GFW封锁，兼容性好，支持各种操作系统

# jeannie感谢大佬JeannieStudio的无私奉献 *Debian 9、10 Ubuntu 16.04 、18.04、19.10 Centos 7、8 *

准备 1.一个域名，推荐namesio(便宜，续费费用不会增加) 2.购买vps，以谷歌云为例

安装 切换到root用户：

sudo -i 执行一键搭建脚本：bash -c "$(curl -fsSL https://raw.githubusercontent.com/cbwbox/jeannie/master/all-install.sh)"

bash -c "$(curl -fsSL https://raw.githubusercontent.com/JeannieStudio/jeannie/master/all-install.sh)" 安装bbr（只是锦上添花，不安装也可以出国）

wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" chmod +x tcp.sh ./tcp.sh 注意事项 别忘了创建防火墙规则，放行80、443、10000这三个端口的出入站，不然，额……你不让人家过，人家怎么帮你转发流量，自然也上不了网喽！

视频链接：https://youtu.be/8PNXSmvqPpI 订阅本频道：https://bit.ly/2X042ea

如果觉得教程不错，不妨给个打赏，创作不易，各位的支持，能激发和鼓励我更大的热情。谢谢！

[root@v163584 ~]# ^C [root@v163584 ~]# firewall-cmd --permanent --zone=public --add-port=1-65535/tcp success [root@v163584 ~]# firewall-cmd --permanent --zone=public --add-port=1-65535/udp success [root@v163584 ~]# firewall-cmd --reload success [root@v163584 ~]# 一、安装证书 #debian&ubuntu

apt-get -y install ca-certificates

#centos

yum -y install ca-certificates

二、安装内核 不卸载内核（安全，若出现不能启动等，可VNC换启动内核）

wget -N --no-check-certificate "https://github.com/ylx2016/Linux-NetSpeed/raw/master/tcpx.sh" && chmod +x tcpx.sh && ./tcpx.sh

卸载内核

wget -N --no-check-certificate "https://github.com/ylx2016/Linux-NetSpeed/raw/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

更新脚本内容

# Merlin for Shadowsocks介绍
version文件 记录了各版本的md5信息
偶数版本较稳定, 3.60为官方最后一个版本,3.6.01是 民间修改 增加了对chain_a的支持
请开启jfs后 根据离线安装中心的提示安装
如无法正常安装 可SSH硬装 以SSH安装3.6.0.1为例:

cd /tmp

wget -N -O shadowsocks.tar.gz https://raw.githubusercontent.com/heweiye/Merlin_Shadowsocks/master/shadowsocks_3.6.0.tar.gz

tar -zxvf /tmp/shadowsocks.tar.gz

chmod +x /tmp/shadowsocks/install.sh

sh /tmp/shadowsocks/install.sh

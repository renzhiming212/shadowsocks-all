
### 特点

一键安装 Shadowsocks-Python， ShadowsocksR， Shadowsocks-Go， Shadowsocks-libev 版（四选一）服务端


### 安装方法

安装wget
```
# centos
yum -y install wget

# Ubuntu
apt-get -y install wget
```

安装服务
```
wget --no-check-certificate https://raw.githubusercontent.com/quniu/shadowsocks-all/master/install/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```

默认密码`abc123456`



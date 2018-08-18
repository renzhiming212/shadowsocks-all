
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


### 相关参考

这是优化修改版，原作者版本请看[这里](https://github.com/teddysun/shadowsocks_install)

原作者站点[shadowsocks.be](https://shadowsocks.be/)

### 相关文章

[Shadowsocks 一键安装脚本（四合一）](https://teddysun.com/486.html)

[ShadowsocksR一键安装脚本](https://shadowsocks.be/9.html)

[Shadowsocks libev版一键安装脚本](https://teddysun.com/357.html)

[shadowsocks-libev-debian版一键安装脚本](https://teddysun.com/358.html)

[Shadowsocks Go版一键安装脚本](https://teddysun.com/392.html)

[Shadowsocks Python版一键安装脚本](https://teddysun.com/342.html)


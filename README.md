# shadowsocks_install
静态编译shadowsocks快速部署服务
#### 服务端部署 #### 

一键执行脚本

```

wget --no-check-certificate -O gost_install.sh https://raw.githubusercontent.com/yiguihai/shadowsocks_install/master/shadowsocks-libev.sh
chmod +x shadowsocks-libev.sh
./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log

```

卸载

```

bash shadowsocks-libev.shuninstall  

```

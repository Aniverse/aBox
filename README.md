# aBox
Bash scripts for dedicated seedbox with root privilege.  

IPv6 配置脚本
```
bash <(wget -qO- https://github.com/Aniverse/aBox/raw/master/scripts/ipv6)
```

iperf 测速脚本
```
bash <(wget -qO- https://github.com/Aniverse/aBox/raw/master/scripts/iperfff)
```

螃蟹卡换 8168 驱动（成功几率不是很高）
```
bash <(wget -qO- https://github.com/Aniverse/aBox/raw/master/scripts/r8168)
```

flexget 配置脚本
```
wget -qO /usr/local/bin/flexgettt https://github.com/Aniverse/aBox/raw/master/scripts/flexgettt
chmod 755 /usr/local/bin/flexgettt
flexgettt
```

-------------------

bench 测试脚本，支持硬盘 4K 性能测试、独服硬盘通电时间检测
```
bash <(wget -qO- https://git.io/ceshi)
```

锐速、bbr、魔改 bbr、bbrplus 脚本
```
bash <(wget -qO- https://git.io/AccTCP)
```

inexistence 客户端安装脚本
```
bash <(wget -qO- https://git.io/abcde)
```

自动挂载 ISO、扫 BDinfo、截图脚本
```
wget -qO /usr/local/bin/bluray https://github.com/Aniverse/bluray/raw/master/bluray
chmod +x /usr/local/bin/bluray
bluray
```

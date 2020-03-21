---
title: "Dns64服务器"
date: 2020-03-21T20:36:25+08:00
draft: true
---

### Dns64 server是什么

你有一台 ipv6的机器，想访问 ipv4的网站，Dns64 server就可以帮助你解决这个问题。

1.修改 dns服务器

```bash
nano /etc/resolv.conf
```

2.删除以前的nameserver ,使用下面这两个

```
nameserver 2001:67c:2b0::4 
nameserver 2001:67c:2b0::6
```

-----

[参考] ：https://wangdalao.com/2913.html

[Trex Dns64 server]：http://www.trex.fi/2011/dns64.html
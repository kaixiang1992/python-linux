
### 1.使用VMware创建虚拟机，[文档地址](https://www.cnblogs.com/bianxcArticle/p/9332842.html)
```markdown
https://www.cnblogs.com/bianxcArticle/p/9332842.html
```

### 2.Linux打开终端
```markdown
Ctrl+Alt+T
```

### 3.输入ifconfig查看ip信息`192.168.184.128`
```markdown
ceshi1@ubuntu:~$ ifconfig
eth0      Link encap:Ethernet  HWaddr 00:0c:29:92:5c:b1  
          inet addr:192.168.184.128  Bcast:192.168.184.255  Mask:255.255.255.0
          inet6 addr: fe80::20c:29ff:fe92:5cb1/64 Scope:Link
          UP BROADCAST RUNNING MULTICAST  MTU:1500  Metric:1
          RX packets:1654 errors:0 dropped:0 overruns:0 frame:0
          TX packets:1437 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:1000 
          RX bytes:1485547 (1.4 MB)  TX bytes:162465 (162.4 KB)
          Interrupt:19 Base address:0x2000 

lo        Link encap:Local Loopback  
          inet addr:127.0.0.1  Mask:255.0.0.0
          inet6 addr: ::1/128 Scope:Host
          UP LOOPBACK RUNNING  MTU:65536  Metric:1
          RX packets:118 errors:0 dropped:0 overruns:0 frame:0
          TX packets:118 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:0 
          RX bytes:9637 (9.6 KB)  TX bytes:9637 (9.6 KB)
```

### 4.xshell链接Linux虚拟机
```markdown
https://blog.csdn.net/fengkuagn123/article/details/79114867
```
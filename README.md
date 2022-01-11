# wakeup_on_lan
局域网远程唤醒(Wakeup On LAN) -- 发送一个Magic Packet到某个MAC地址

## Magic Packet
UDP广播包，端口不限，数据是FF-FF-FF-FF-FF-FF加16个MAC

## 编译
cl wol.cpp ws2_32.lib

## 来源
https://www.cnblogs.com/cnLiou/archive/2005/06/20/3131176.html

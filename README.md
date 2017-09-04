# 这是迅雷云监工docker版
by:wsw

***
## 版本说明
***
- :0723，为07月23日更新代码


云监工程序docker版，以`tutum/ubuntu:trusty`为母镜像  

适用于所有docker平台  

外接卷路径`/var/lib/redis`，就是redis数据库存放目录  

容器端口云监工端口4000 SSH端口22，可以SSH到容器，root密码在日志查找  

此云监工源代码提取自 https://github.com/xyz9836/wsw_bao.git 

不足之处：服务器时区不是北京时区，不能定时重启云监工，这些都需要ssh或控制台自己实现  

***

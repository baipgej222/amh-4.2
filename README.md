#AMH 4.2 - 麦葱修改版

> 添加 pcre-8.36

> 添加 zlib-1.2.8

> 添加 openssl-1.0.2a

> 添加 gperftools-2.4

> 添加 ngx_cache_purge-2.3

> 添加 ngx_pagespeed-1.9.32.3

> 添加 ngx_http_substitutions_filter_module : https://github.com/yaoweibin/ngx_http_substitutions_filter_module

> 替换 php-5.3.27 为 php-5.6.8

> 替换 nginx-1.4.7 为 tengine-2.1.0

> 替换 mysql-5.5.34 为 mysql-5.6.24

> 更改 mysql 数据保存位置为 /home/mysql_data 

> 修改错误提示页


**发布页**

http://www.yuxiaoxi.com/2015-01-13-amh-mc.html

目前只用 CentOS 6.6 做了测试，更多测试请等待麦葱更新~

**使用方法**

1、安装 wget 和 screen 命令

Centos:

`yum install -y wget`

`yum install -y screen`

Debian/Ubuntu:

`apt-get install wget`

`apt-get install -y screen`

2、然后运行安装命令

`screen -S installAMH`

`wget https://raw.githubusercontent.com/maicong/amh-4.2/master/amh-mc.sh && bash amh-mc.sh 2>&1 | tee amh-mc.log`

更多模块可在管理面板进行安装。


**免责声明**

- 本项目未做大量测试；

- 本项目不保证兼容性；

- 本项目BUG修复视是否空闲而定；

- 本项目为麦葱自用，会根据需要进行修改，若您不喜，请安装官方原版；

- 麦葱不提出本项目任何技术支持，若需技术支持请移步 amh.sh；

- 开源是精神，不是义务

**预览图**

![](http://ww4.sinaimg.cn/large/67f51f75gw1ervwvpevs5j20et0begp5.jpg)
![](http://ww3.sinaimg.cn/large/67f51f75gw1ervwwutz3wj20us06f447.jpg)
![](http://ww2.sinaimg.cn/large/67f51f75gw1ervwx06zgnj20eu03sgmm.jpg)
![](http://ww3.sinaimg.cn/large/67f51f75gw1ervwx4t7ojj20i701z3yy.jpg)
![](http://ww3.sinaimg.cn/large/67f51f75gw1ervwxbt3dwj20wq0sjqau.jpg)
![](http://ww3.sinaimg.cn/large/67f51f75gw1ervwxgneauj20wq0sytgl.jpg)
![](http://ww2.sinaimg.cn/large/67f51f75gw1ervwxks337j20wq0syk36.jpg)

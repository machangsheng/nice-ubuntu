# nice-ubuntu
make ubuntu easy use


#ubuntu安装后该做什么事？

###Ubuntu 如何开启 SSH ?
####1、安装SS
>`sudo apt-get install openssh-client`   # 用来登录别的机器的SSH  
`sudo apt-get install openssh-server`   # 用来开放本机的SSH服务

####2、启动SSH
>`sudo service ssh start`  # **或**   `sudo /etc/init.d/ssh start`

####3、修改SSH配置文件
>`sudo vim /etc/ssh/sshd_config`   #修改SSH的服务端口，默认端口是22

####4、登录下试试
>`ssh username @192.168.137.100`  # username 为 192.168.137.100 机器上的用户，然后输入密码确认即可

``` c
//写个C语言
#include <stdio.h>
int main (void)
{
  printf ("hello,world");
  return 0;
}
```

#标题1
##标题2
###标题3
####标题4
#####标题5
######标题6

>有序列表
- 文本一
- 文本二
- 文本三

****

>有序列表
1. 文本一
2. 文本二
3. 文本三


###链接
[123](www.baidu.com)
![](http://img.voidcn.com/vcimg/000/001/489/340_b66_519.jpg)


###表格
|1|2|3|
|:--|:--|:--|
|4|5|6|
|7|8|9|


- []yi
- [x]





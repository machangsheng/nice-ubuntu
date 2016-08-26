# nice-ubuntu
make ubuntu easy use

#Ubuntu 如何开启 SSH ?
##1、安装SS
>'sudo apt-get install openssh-client'# 用来登录别的机器的SSH  
'sudo apt-get install openssh-server'# 用来开放本机的SSH服务

##2、启动SSH
>'sudo service ssh start'  # 或 sudo /etc/init.d/ssh start

##3、修改SSH配置文件
>'sudo vim /etc/ssh/sshd_config'   #修改SSH的服务端口，默认端口是22

##4、登录下试试
>'ssh username @192.168.137.100'  # username 为 192.168.137.100 机器上的用户，然后输入密码确认即可

... c





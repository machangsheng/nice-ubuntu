# nice-ubuntu
make ubuntu easy use


#ubuntu安装后该做什么事？

>####必做
>>1. 打开软件更新器，联网下载更新然后重启   
2. 终端执行`sudo gedit /etc/resolv.conf`更改以后执行`sudo apt-get update`
3. windows和ubuntu时间同步`sudo timedatectl set-local-rtc 1`
4. 点击图标最小化`gsettings set org.compiz.unityshell:/org/compiz/profiles/unity/plugins/unityshell/ launcher-minimize-window true
`  

>####美化
>>1. 终端执行`sudo apt-get install unity-tweak-tool`
2. 终端执行`mkdir .themes`,将解压后的图标包放进***themes***文件夹
3. 安装主题   
 
>####安装软件
>>1. 安装谷歌



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

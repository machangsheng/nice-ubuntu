1.安装zsh`sudo apt-get install zsh`

   确认是否安装成功`zsh --version`



2.置zsh为默认shell`sudo chsh -s $(which zsh)`或者`sudo chsh -s /usr/bin/zsh`

​    确认zsh是否是默认SHELL `echo $SHELL`



3.接下来我们需要下载 oh-my-zsh 项目来帮我们配置 zsh，采用wget安装,这里需要先安装git，而且要以管理员权限运行.

- `sudo apt-get install git`

- - 使用wget安装： `sudo wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh`
  - 或者使用curl方式安装：`sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

  ​



4.Oh-my-zsh的默认配置文件在：`~/.zshrc`

- 编辑~/.zshrc修改主题为：***agnoster***

- 在`~/.zshrc`中添加**`export DEFAULT_USER="whoami"`**, 可以隐藏固定的 user@hostname 信息。

- 修改*`agnoster`*主题的字体

  > 下载地址[https://github.com/powerline/fonts](https://github.com/powerline/fonts)

  > 下载***Ubuntu Mono derivative Powerline***字体后双击安装








# 超强vim配置文件

感谢原作者ma6174的辛勤劳动。
我感觉其对c++的自动补全功能不是很完善，加了OmniCppComplete和c++的tags
添加了F4对ctags的支持功能

我基本是小白，不敢改动太多。

[![Build Status](https://travis-ci.org/ma6174/vim.png?branch=master)](https://travis-ci.org/ma6174/vim)

### 运行截图

![screenshot.png](screenshot.png)

### 简易安装方法：

打开终端，执行下面的命令就自动安装好了：

`wget -qO- https://raw.github.com/zhaoyihong/vim/master/setup.sh | sh`

### 或者自己手动安装：(以ubuntu为例)

1. 安装vim `sudo apt-get install vim`
- 安装ctags：`sudo apt-get install ctags`
- 安装一些必备程序：`sudo apt-get install python-twisted xclip vim-gnome astyle python-setuptools`
- python代码格式化工具：`sudo easy_install -ZU autopep8`
- `sudo ln -s /usr/bin/ctags /usr/local/bin/ctags`
- clone配置文件：`cd ~/ && git clone git://github.com/zhaoyihong/vim.git`
- `mv ~/vim ~/.vim`
- `mv ~/.vim/.vimrc ~/`
- clone bundle 程序：`git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle`
- 打开vim并执行bundle程序`:BundleInstall`
- 重新打开vim即可看到效果

### 了解更多vim使用的小技巧：

[tips.md](tips.md)

### 查看更新日志：

[`update_log.md`](update_log.md)

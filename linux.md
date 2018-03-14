[TOC]

# Linux通用

* 传送文件
`scp C:\Users\Administrator\Desktop\Temp\meizi\all_file kim@192.168.1.132:/home/kim/project/meizi/all_file`

## 查看内存
* `free`
* `top`
* `htop`更直观

## 安装ZSH

```
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
# 默认启动ZSH
chsh -s /bin/zsh
```
* 通配符的Bug
> 
```
vim ~/.zshrc
# add next line
setopt no_nomatch

```

# Linux Deploy

> 在安卓手机上安装Linux系统,但是安装的系统需支持ARM架构.
> 安装的centos-altarch,yum源的支持不是太好.

## 安装步骤
1. 配置文件

2. 安装
3. 启动
4. 文件传输
`scp D:/Catalog/Django/maxone.zip kim@192.168.1.132:/home/kim/project`

# Debian

## 查看已安装的软件

`dpkg -l | grep soft-name`

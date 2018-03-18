[TOC]

# Linux��װ

## ��������

* ���Ƕ��ϵͳ��

|SWAP|home|��չ����|
|-|-|-|

|��չ����...|Debian/|CentOS/|Arch/ ...|
|-|-|-|-|

# Linuxͨ��

* �����ļ�  
`scp C:\Users\Administrator\Desktop\Temp\meizi\all_file kim@192.168.1.132:/home/kim/project/meizi/all_file`

## �鿴�ڴ�
* `free`
* `top`
* `htop`��ֱ��

# Ч���๤��

## ��װZSH

```
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
# Ĭ������ZSH
chsh -s /bin/zsh
```
* ͨ�����Bug

`find . -name *.h`
`no matches found`

* ���

```
# vim ~/.zshrc 
# add
setopt no_nomatch
source ~/.zshrc
```

## tmux

## vim

# Linux Deploy on Andriod

> �ڰ�׿�ֻ��ϰ�װLinuxϵͳ,���ǰ�װ��ϵͳ��֧��ARM�ܹ�.
> ��װ��centos-altarch,yumԴ��֧�ֲ���̫��.

## ��װ����
1. �����ļ�
     * Դ��ַ
       ѡ���ٶȿ�һ�㣬���пƴ�����廪  
       `https://mirror.tuna.tsinghua.edu.cn/archlinuxarm/`  
     * ��װ·��  
       `/mnt/sdcard/linux/arch/arch.img/  # linux���ļ��о������ֻ��ڴ��Ŀ¼��`


2. ��װ
3. ����
4. �ļ�����
`scp D:/Catalog/Django/maxone.zip kim@192.168.1.132:/home/kim/project`




# Debian 9

## [��װ�Կ�����](https://wiki.debian.org/AtiHowTo#AMD.2FATI_Open_Source_Drivers_.28amdgpu.2C_radeon.2C_r128.2C_mach64.29)
�°�װ��ϵͳ����û�а�װ�������ο�������ַ

```
# Debian 8 "Jessie"
deb http://httpredir.debian.org/debian/ jessie main contrib non-free

apt-get update

apt-get install firmware-linux-nonfree libgl1-mesa-dri xserver-xorg-video-ati
```

## ֱ������������ϵͳ

* �ο�<https://www.cnblogs.com/qingkai/p/5443572.html>

* �޸�grub��

`sudo nano /etc/default/grub`

* �޸���������

```
...
GRUB_CMDLINE_LINUX_DEFAULT="quiet"
GRUB_CMDLINE_LINUX=""
...
#GRUB_TERMINAL=console
```

Ϊ

```
...
#GRUB_CMDLINE_LINUX_DEFAULT="quiet"
GRUB_CMDLINE_LINUX="text"
...
GRUB_TERMINAL=console
```

* ����grub
`sudo update-grub`

* ����systemd
`sudo systemctl set-default multi-user.target`

* ���Ҫ�л�ͼ�ν���, ��ת���ϲ��裬ִ��һ������

`systemctl set-default graphical.target`

* reboot  
* �����������Ҫ����x window��ֱ��`startx`
> ������`sudo systemctl start lightdm.servic`

## ��������

`sudo alasmixter`

* ���ÿ�ݼ�
```
����������  
amixer set Master 5%+  
����������  
amixer set Master 5%-  
������  
amixer set Master toggle
```
## ���Դ

* <https://www.debian.org/mirror/list>

```
ftp2.cn.debian.org ftp.cn.debian.org mirror.lzu.edu.cn mirrors.163.com  mirrors.tuna.tsinghua.edu.cn mirrors.ustc.edu.cn mirrors.xjtu.edu.cn 
```
* ʹ��netselect(��Ҫ��װ)�����ٶ�
> ����ʹ��netselect-apt�����ֱ�������ٶ�������Դ��sources.list

## rime���뷨
`sudo apt install ibus-rime`
`sudo apt install librime-data-double-pinyin`

## ����

* 
`wget https://github.com/downloads/adobe-fonts/source-code-pro/SourceCodePro_FontsOnly-1.013.zip`

* ��ѹ
`unzip SourceCodePro_FontsOnly-1.013.zip`

* ����
`cp -r ~/Downloads/SourceCodePro_FontsOnly-1.013/OTF/. ~/.fonts`

* ִ��
`fc-cache -f -v`

* ���ն���ʹ��Source Code Pro ����

## �鿴�Ѱ�װ�����

`dpkg -l | grep soft-name`

## ssh server
```
sudo  apt-get install openssh-server
#ssh����״̬
ps -s|grep ssh
#��������
service ssh start
```
## ��¼iso��U��
`dd bs=4M if=/home/debian/archlinux.iso of=/dev/sdb status=progress && sync`

## ��������ΪӢ��
`sudo vi /etc/default/locale`  
```
LANG="en_US.UTF-8"
LANGUAGE="en_US:en"
```
`reboot`

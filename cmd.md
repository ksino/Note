[TOC]

# Windows命令行
## 1. help
```
 help cd
显示当前目录名或改变当前目录。

CHDIR [/D] [drive:][path]
CHDIR [..]
CD [/D] [drive:][path]
CD [..]

  ..   指定要改成父目录。

键入 CD drive: 显示指定驱动器中的当前目录。
不带参数只键入 CD，则显示当前驱动器和目录。
```
## 2. tree遍历目录写入文本文件

```
tree /f>list.txt
```
# Linux命令行
## 1. help
```
ls --help
Usage: ls [OPTION]... [FILE]...
List information about the FILEs (the current directory by default).
Sort entries alphabetically if none of -cftuvSUX nor --sort is specified.

Mandatory arguments to long options are mandatory for short options too.
  -a, --all                  do not ignore entries starting with .
  -A, --almost-all           do not list implied . and ..
      --author               with -l, print the author of each file
...
```
## 2. ls  显示文件或目录
```
$ ls       # 仅列出当前目录可见文件
$ ls -l    # 列出当前目录可见文件详细信息
$ ls -hl   # 列出详细信息并以可读大小显示文件大小
$ ls -al   # 列出所有文件（包括隐藏）的详细信息
```

## 3. mkdir  创建目录
```
$ mkdir -p folder/subfolder
# -p 参数为当父目录存在时忽略，若不存在则建立，用此参数可建立多级文件夹
```

## 4. cd               切换目录

touch          创建空文件

echo            创建带有内容的文件。

## 5. cat (用于输出文件内容到 Terminal)
```
$ cat /etc/locale.gen     ### 输出 locale.gen 的内容
$ cat -n /etc/locale.gen  ### 输出 locale.gen 的内容并显示行号
```

## 6. cp (copy, 复制文件)
```
$ cp source dest            ### 将 source 复制到 dest
$ cp folder/*  dest         ### 将 folder 下所有文件(不含子文件夹中的文件)复制到 dest
$ cp -r folder  dest        ### 将 folder 下所有文件（包含子文件夹中的所有文件）复制到 dest
```

## 7. mv (移动或重命名)

## 8. rm (remove, 删除文件)
    * -r            递归删除，可删除子目录及文件
    * -f            强制删除
```
$ rm filename
### 删除 filename
$ rm -i filename
### 删除 filename 前提示，若多个文件则每次提示
$ rm -rf folder/subfolder/
### 递归删除 subfolder 下所有文件及文件夹，包括 subfolder 自身
$ rm -d folder
###  删除空文件夹
```
## 9. pwd(显示当前目录)

# cmder
> [设置参考](https://zhuanlan.zhihu.com/p/28400466)

1. 修改命令提示符λ为$(ps.更改后,可以修正,重复上一条命令的错误字符)

   进入解压后的cmder的目录，进入vendor,打开init.bat文件。
   修改第15行的代码

   ```
   @prompt $E[1;32;40m$P$S{git}{hg}$S$_$E[1;30;40m{lamb}$S$E[0m
   ```

   改为:

   ```
   @prompt $E[1;32;40m$P$S{git}{hg}$S$_$E[1;30;40m $$ $S$E[0m
   ```

   修改前后:
   ![img](http://images2015.cnblogs.com/blog/743207/201612/743207-20161217183242448-1393899446.png)
   ![img](http://images2015.cnblogs.com/blog/743207/201612/743207-20161217183252839-2126921017.png)

   新版的cmder(2016.11.3测试)单纯修改init.bat或以前的方法都试过了不行，下面是我自己找到的方法。亲测可行。
   cmder\vendor\clink.lua文件中第41行中{lamb}修改为$
   修改前：
   `local cmder_prompt = "\x1b[1;32;40m{cwd} {git}{hg} \n\x1b[1;30;40m**{lamb}** \x1b[0m"`
   修改后：
   `local cmder_prompt = "\x1b[1;32;40m{cwd} {git}{hg} \n\x1b[1;30;40m**$** \x1b[0m"`

   参考<http://blog.csdn.net/tangketan/article/details/77657917>

   按其修改虽可,但高亮颜色又没有了.

   发现修改代码可行,重复字符问题是因为'λ'

   修改set_prompt_filter,48行,51行的符号如'$'或'>'

   ```lua
    if env == nil then
           -- lambda = "λ"
           lambda = "$"
       else
           -- lambda = "("..env..") λ"
           lambda = "("..env..") $"
       end
   ```

   ​

2. ## 添加至右键菜单

   ------

   进入cmder的根目录执行注册要右键菜单即可。

   ```
   C:\Windows\system32>d:

   D:\>cd cmder

   D:\cmder>Cmder.exe /REGISTER ALL
   ```
   ### 3.命令简化

   打开`C:\Program Files (x86)\cmder\config\user-aliases.cmd`

   * example: `djsp=django-admin startproject $* #后面的符号等同于此命令可外接其他参数`

     <https://jeffjade.com/2016/01/13/2016-01-13-windows-software-cmder/>

## cmder的编码问题

* 爬虫使用cmder打印的时候，时常会出现gbk 转utf-8的[问题](https://www.crifan.com/unicodeencodeerror_gbk_codec_can_not_encode_character_in_position_illegal_multibyte_sequence/)

`Settings > Startup > Environment`
添加`chcp 65001`
> 通过 chcp命令改变代码页，UTF-8的代码页为65001
     ​


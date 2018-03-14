[TOC]

# sublime

## subl命令

> 添加sublime所在路径到环境变量,命令行subl打开sublime
>
> 

## Packages

> 如果package control不能安装插件,可以尝试将源码直接放到该目录下

> `D:\Program Files\Sublime Text 3.3126x64\Data\Packages`

### 1. OmniMarkupPreviewer

* 打开配置：

>Sublime Text > Preferences > Package Settings ><br/>
>OmniMarkupPreviewer > Settings - User

* 去除extensions配置中的 strikeout ,修改为如下
```python
{
    "renderer_options-MarkdownRenderer": {
        "extensions": ["tables", "fenced_code", "codehilite"]
    }
}
```
+ [参考网页](http://blog.csdn.net/gsying1474/article/details/53642097)

+ 配置固定IP,局域网内其他机器可以直接访问

  `192.168.1.130:51004/view/99`

### 2. [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel)

* 自动补全

```python
{
    "codeintel_language_settings": {
        "Python": {
            // python virtualenv
            "python": "C:\\env\\maxdj\\Scripts\\python.exe",
            //排除扫描的路径
            "codeintel_scan_extra_dir": [],
            "codeintel_scan_files_in_project": true,
            //扫描层级
            "codeintel_max_recursive_dir_depth": 15,
            //扫描的目录
            "codeintel_scan_exclude_dir":[
                "C:\\env\\maxdj\\Lib\\site-packages",
                "C:\\env\\maxdj\\Lib\\*",
            ],
        },
    }
}
```

* jump to definition

  For Windows:

  - Jump to definition = `Alt+Click`
  - Jump to definition = `Control+Windows+Alt+Up`
  - Go back = `Control+Windows+Alt+Left`
  - Manual Code Intelligence = `Control+Shift+space`

* [sublime text3 python代码自动提示](http://blog.csdn.net/m1mory/article/details/72582661)

### 3. [Djaneiro](https://github.com/squ1b3r/Djaneiro)

> Djaneiro 支持 Django 模版和关键字高亮以及许多实用的代码片(snippets)功能

## 快捷键列表
* Notice

>["ctrl+k", "ctrl+b"]<br>
>意思是先按"ctrl+k"，再按"ctrl+b"，快捷键才能生效。<br>
>如这个快捷键就是打开关闭side bar

### 通用

* ↑↓←→ ：上下左右移动光标。
* alt：调出菜单
* **`ctrl + shift + p`**：调出命令板（command palette）
* **<code>ctrl + `</code>** ：调出控制台

### 编辑

* `ctrl + enter`：在当前行下面新增一行然后跳至该行
* `ctrl + shift + enter`：在当前行上面增加一行并跳至该行
* `ctrl + ←/→`：进行逐词移动
* `ctrl + shift + ←/→`进行逐词选择
* `ctrl + ↑/↓`移动当前显示区域
* `ctrl + shift + ↑/↓`移动当前行

### 选择

* `ctrl+d`：选择当前光标所在的词并高亮该词所有出现的位置，<br>再次 ctrl + d 选择该词出现的下一个位置，在多重选词的过程中，<br>使用 ctrl + k 进行跳过，使用 ctrl + u 进行回退，使用 esc 退出多重编辑
* `ctrl + shift + l`：将当前选中区域打散
* `ctrl + j`：把当前选中区域合并为一行
* `ctrl + m`：在起始括号和结尾括号间切换
* `ctrl + shift + m`：快速选择括号间的内容
* `ctrl + shift + j`：快速选择同缩进的内容
* `ctrl + shift + space`：快速选择当前作用域（scope）的内容

### 查找替换

* `f3`：跳至当前关键字下一个位置
* `shift + f3`：跳到当前关键字上一个位置
* `alt + f3`：选中当前关键字出现的所有位置
* `ctrl + f/h`：进行标准查找/替换，之后：
* `alt + c`：切换大小写敏感（case-sensitive）模式
* `alt + w`：切换整字匹配（whole matching）模式
* `alt + r`：切换正则匹配（regex matching）模式
* `ctrl + shift + h`：替换当前关键字
* `ctrl + alt + enter`：替换所有关键字匹配
* `ctrl + shift + f`：多文件搜索&替换

### 跳转

* **`ctrl + p`**：跳转到指定文件，输入文件名后可以：

> `@` 符号跳转：输入 @symbol 跳转到 symbol 符号所在的位置<br>
> `#` 关键字跳转：输入 \# keyword 跳转到 keyword 所在的位置<br>
> `:` 行号跳转：输入 :12 跳转到文件的第12行。

* **`ctrl + r`**：跳转到指定符号
* **`ctrl + g`**：跳转到指定行号
* **`alt + -`**： 上一个编辑处
* **`alt + shift + -`**： 下一个编辑处

### 窗口

* `ctrl + shift + n`：创建一个新窗口
* `ctrl + n`：在当前窗口创建一个新标签
* `ctrl + w`：关闭当前标签，当窗口内没有标签时会关闭该窗口
* `ctrl + shift + t`：恢复刚刚关闭的标签
* `ctrl+k, shift+left`: carry_file_to_pane
* `ctrl+k, ctrl+shift+right`: destroy_pane

### 屏幕

* `f11`：切换普通全屏
* `shift + f11`：切换无干扰全屏
* `alt + shift + 2`：进行左右分屏
* `alt + shift + 8`：进行上下分屏
* `alt + shift + 5`：进行上下左右分屏
* 分屏之后，使用 ctrl + 数字键 跳转到指定屏，<br>使用 ctrl + shift + 数字键 将当前屏移动到指定屏

### 设置
#### 不同语言设置不同缩进
> `D:\Program Files\Sublime Text 3.3126x64\Data\Packages\User`

打开某个语言的文件后,再点击
菜单栏: `Preferences -> Settings - More -> Syntax Specific - User`
```
{
    "tab_size": 2,
    "translate_tabs_to_spaces": true
}
```
这样就会自动设置好配置名字

## 正则表达式

Find what

`\.\./((?<=\.\./)[^'"]+)`

Replace with

`{% static'$1' %}	#第1个括号查找的文本为$1`

原文

`../css/reset.css`

替换后

`{% static'css/reset.css' %}`

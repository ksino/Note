[TOC]

<span id="jump">跳转至此</span>


## 段落和换行

一个 Markdown 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行

「由一个或多个连续的文本行组成」这句话其实暗示了 Markdown 允许段落内的强迫换行（插入换行符`<br />`），这个特性和其他大部分的 text-to-HTML 格式不一样（包括 Movable Type 的「Convert Line Breaks」选项），其它的格式会把每个换行符都转成 <br /> 标签。

如果你确实想要依赖 Markdown 来插入 <br /> 标签的话，在插入处先按入两个以上的空格然后回车。

的确，需要多费点事（多加空格）来产生 <br /> ，但是简单地「每个换行都转换为 <br />」的方法在 Markdown 中并不适合， Markdown 中 email 式的 区块引用 和多段落的 列表 在使用换行来排版的时候，不但更好用，还更方便阅读。

##标题

Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。

* 类 Setext, 任何数量的 = 和 - 都可以有效果。
```
最高阶标题
=============

第二阶标题
-------------
```
最高阶标题
=============

第二阶标题
-------------

* 类 Atx 形式则是标题 1 到 6 阶
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题


## 区块引用

Markdown 标记区块引用是使用类似 email 中用 > 的引用方式。如果你还熟悉在 email 信件中的引言部分，你就知道怎么在 Markdown 文件中建立一个区块引用，那会看起来像是你自己先断好行，然后在每行的最前面加上 > ：
```
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
```
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Markdown 也允许你偷懒只在整个段落的第一行最前面加上 > ：
```
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.
```

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > ：
```
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.
```

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

引用的区块内也可以使用其他的 Markdown 语法，包括标题、列表、代码区块等：

```
> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");
```

> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

## 列表

Markdown 支持有序列表和无序列表。

无序列表使用星号、加号或是减号作为列表标记：
```
*   Red
*   Green
*   Blue
```
*   Red
*   Green
*   Blue

等同于：
```
+   Red
+   Green
+   Blue
```
+   Red
+   Green
+   Blue

等同于：
```
-   Red
-   Green
-   Blue
```
-   Red
-   Green
-   Blue

有序列表则使用数字接着一个英文句点：
```
1.  Bird
2.  McHale
3.  Parish
```
1.  Bird
2.  McHale
3.  Parish


如果你的列表标记写成：
```
1.  Bird
1.  McHale
1.  Parish
```
1.  Bird
1.  McHale
1.  Parish

或甚至是：
```
3. Bird
1. McHale
8. Parish
```
3. Bird
1. McHale
8. Parish

要让列表看起来更漂亮，你可以把内容用固定的缩进整理好：
```
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.
```

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

但是如果你懒，那也行：
```
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.
```

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.

列表项目可以包含多个段落，每个项目下的段落都必须缩进 4 个空格或是 1 个制表符：

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

如果你每行都有缩进，看起来会看好很多，当然，再次地，如果你很懒惰，Markdown 也允许：

*   This is a list item with two paragraphs.

    This is the second paragraph in the list item. You're
only required to indent the first line. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit.

*   Another item in the same list.

如果要在列表项目内放进引用，那 > 就需要缩进：
```
*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
```

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

如果要放代码区块的话，该区块就需要缩进两次，也就是 8 个空格或是 2 个制表符：
```
*   一列表项包含一个列表区块：

        <代码写在这>
```
*   一列表项包含一个列表区块：

        <代码写在这>
当然，项目列表很可能会不小心产生，像是下面这样的写法：

## 代码区块

要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以，例如，下面的输入：

这是一个普通段落：

    这是一个代码区块。

这个每行一阶的缩进（4 个空格或是 1 个制表符），都会被移除，例如：

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

一个代码区块会一直持续到没有缩进的那一行（或是文件结尾）。

在代码区块里面， & 、 < 和 > 会自动转成 HTML 实体，这样的方式让你非常容易使用 Markdown 插入范例用的 HTML 原始码，只需要复制贴上，再加上缩进就可以了，剩下的 Markdown 都会帮你处理，例如：

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

## 分隔线

你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：
```
1
***
2
* * *
3
---
4
- - -
5
___
6
_ _ _
```
1
***
2
* * *
3
---
4
- - -
5
___
6
_ _ _

## 区段元素

### 链接

Markdown 支持两种形式的链接语法：

* 行内式
```
[行内式](网址 "可选链接说明文字")

[百度搜索](https://www.baidu.com/ "时间只解催人老")

[This link](http://example.net/) has no title attribute.
```
[百度搜索](https://www.baidu.com/ "时间只解催人老")

[This link](http://example.net/) has no title attribute.


如果你是要链接到同样主机的资源，你可以使用相对路径：
```
See my [About](/about/) page for details.
```
See my [About](/about/) page for details.

* 参考式

参考式超链接一般用在学术论文上面，或者另一种情况，如果某一个链接在文章中多处使用，那么使用引用 的方式创建链接将非常好，它可以让你对链接进行统一的管理。
```
This is [an example][id] reference-style link.
```
This is [an example][id] reference-style link.

你也可以选择性地在两个方括号中间加上一个空格：
```
This is [an example] [id] reference-style link.
```
This is [an example] [id] reference-style link.

接着，在文件的任意处，你可以把这个标记的链接内容定义出来：
```
[id]: http://example.com/  "Optional Title Here"
```
[id]: http://example.com/  "Optional Title Here"
链接内容定义的形式为：

方括号（前面可以选择性地加上至多三个空格来缩进），里面输入链接文字
接着一个冒号
接着一个以上的空格或制表符
接着链接的网址
选择性地接着 title 内容，可以用单引号、双引号或是括弧包着
下面这三种链接的定义都是相同：
```
[foo]: http://example.com/  "Optional Title Here"
[foo]: http://example.com/  'Optional Title Here'
[foo]: http://example.com/  (Optional Title Here)
```

链接网址也可以用方括号包起来：
```
[id]: <http://example.com/>  "Optional Title Here"
```
你也可以把 title 属性放到下一行，也可以加一些缩进，若网址太长的话，这样会比较好看：
```
[id]: http://example.com/longish/path/to/resource/here
    "Optional Title Here"
```
网址定义只有在产生链接的时候用到，并不会直接出现在文件之中。

链接辨别标签并不区分大小写，

隐式链接标记功能让你可以省略指定链接标记，这种情形下，链接标记会视为等同于链接文字，要用隐式链接标记只要在链接文字后面加上一个空的方括号，如果你要让 "Google" 链接到 google.com，你可以简化成：
```
[Google][]
```
[Google][]

然后定义链接内容：
```
[Google]: http://google.com/
```
[Google]: http://google.com/
由于链接文字可能包含空白，所以这种简化型的标记内也许包含多个单词：
```
[Daring Fireball][]
```
Visit [Daring Fireball][] for more information.
然后接着定义链接：
```
[Daring Fireball]: http://daringfireball.net/
```
[Daring Fireball]: http://daringfireball.net/
链接的定义可以放在文件中的任何一个地方，我比较偏好直接放在链接出现段落的后面，你也可以把它放在文件最后面，就像是注解一样。

下面是一个参考式链接的范例：
```
I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
```
I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
如果改成用链接名称的方式写：
```
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
```
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"

下面是用行内式写的同样一段内容的 Markdown 文件，提供作为比较之用：
```
I get 10 times more traffic from [Google](http://google.com/ "Google")
than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or
[MSN](http://search.msn.com/ "MSN Search").
```
I get 10 times more traffic from [Google](http://google.com/ "Google")
than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or
[MSN](http://search.msn.com/ "MSN Search").

参考式的链接其实重点不在于它比较好写，而是它比较好读，比较一下上面的范例，使用参考式的文章本身只有 81 个字符，但是用行内形式的却会增加到 176 个字元，如果是用纯 HTML 格式来写，会有 234 个字元，在 HTML 格式中，标签比文本还要多。

使用 Markdown 的参考式链接，可以让文件更像是浏览器最后产生的结果，让你可以把一些标记相关的元数据移到段落文字之外，你就可以增加链接而不让文章的阅读感觉被打断。

## 强调

使用星号（\*）和底线（_）作为标记强调字词的符号，如果 * 和 _ 两边都有空白的话，它们就只会被当成普通的符号.
```
*我是斜体*

**你是粗体**

***他是加粗斜体***

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__
```
*我是斜体*

**你是粗体**

***他是加粗斜体***

_single underscores_

**double asterisks**

__double underscores__

## 代码

标记行内代码，可以用反引号把它包起来（`）.
```
Use the `printf()` function.
```
Use the `printf()` function.

如果要在代码区段内插入反引号，你可以用多个反引号来开启和结束代码区段：

``There is a literal backtick (`) here.``

代码区段的起始和结束端都可以放入一个空白，起始端后面一个，结束端前面一个，这样你就可以在区段的一开始就插入反引号：
```
`` ` ``
```
A single backtick in a code span: `` ` ``
```
`` `foo` ``
```
A backtick-delimited string in a code span: `` `foo` ``


```html
<a href="https:www.baidu.com"></a>
```

## 图片

Markdown 使用一种和链接很相似的语法来标记图片，同样也允许两种样式： 行内式和参考式。

如果需要的指定图片的宽高话，使用普通的 `<img>` 标签。

* 行内式的图片语法
```
![图片的替代文字](网址, '说明文字')
![Alt text](/path/to/img.jpg "Optional title")
```

![Alt](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1505490071928&di=21523a3b27ae15229916b70ee64acc41&imgtype=0&src=http%3A%2F%2Fdynamic-image.yesky.com%2F143x107%2FuploadImages%2F2016%2F221%2F49%2F82FBBC118611.jpg "亲吻")

* 参考式
```
![Alt text][id]
[id]: url/to/image  "Optional title attribute"
```

![Alt text][id]
[id]: https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1505490071935&di=f63d96d6f65e6ed746274c8920754e35&imgtype=0&src=http%3A%2F%2Fimg.51ztzj.com%2Fupload%2Fimage%2F20141021%2Fsj201410211023_220x138.jpg "美女"



## 其它

### 自动链接

用方括号将链接包起来，自动转成链接。
```
<http://example.com/>
```
<http://example.com/>

```
<address@example.com>
```
<address@example.com>



### 反斜杠

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：
```
\\   反斜线
\`   反引号
\*   星号
\_   底线
\{}  花括号
\[]  方括号
\()  括弧
\#   井字号
\+   加号
\-   减号
\.   英文句点
\!   惊叹号
```
\\   反斜线
\`   反引号
\*   星号
\_   底线
\{}  花括号
\[]  方括号
\()  括弧
\#   井字号
\+   加号
\-   减号
\.   英文句点
\!   惊叹号
## 锚点 


```html
[跳转位置](#jump)

<span id="jump">说明文字</span>
```

# 表格
* 简单方式写表格：
```
学号|姓名|分数
-|-|-
小明|男|75
小红|女|79
小陆|男|92
```
学号|姓名|分数
-|-|-
小明|男|75
小红|女|79
小陆|男|92

* 原生方式写表格：
```
|学号|姓名|分数|
|-|-|-|
|小明|男|75|
|小红|女|79|
|小陆|男|92|
```
|学号|姓名|分数|
|-|-|-|
|小明|男|75|
|小红|女|79|
|小陆|男|92|

* 为表格第二列指定方向：默认为左对齐，在-右边加上:就右对齐(-:)
```
产品|价格
-|-:
Leanote 高级|60元/年
Leanote 超级账号|120元/年
```
产品|价格
-|-:
Leanote 高级|60元/年
Leanote 超级账号|120元/年

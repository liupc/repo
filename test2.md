##<center>How To Use Markdown quickly!</center>##
*前言*
markdown是一种轻量级的标记语言，与html不同的是，它设计的目的就是让文档的可读性更高，让格式直接成为文档书写的一部分，而不是像office那样，后期去通过各种工具和按钮来修改装饰。

html拥有的标记，在markdown里面都能够使用，但是，markdown本身的标记是被简化和重新设计过的。不过在html标记里面会disable掉本身的标记特性，因此，想要同时使用markdown的标记带来的格式和html的标记，需要将markdown标记置于html标记外层。像我的title其实就是在`##`内部包含了`<center>`标签。

markdown貌似首行都不提供默认的缩进标签，可能是默认就不缩进的样式。

*推荐的工具和平台*：

**linux**

Chrome插件( [StackEdit](https://chrome.google.com/webstore/search/stackedit?hl=en-US) ) - online and offline tools for markdown intime editor, you can post your .md file to blog system or save them on goolge drive and dropbox right after finish your edit (however i use wiznote).

**windows**

MarkdownPad - offline markdown editor, surprisingly found their home page was build on Bootstrap2

**online editor**
Strongly recommend the http://dillinger.io/ website, I have tested different editor may have small view styles difference.but **dillinger.io** almost perfect. 

*这是一个测试文件*

###标题1

* * *
我们需要一种探索新技术的勇气

####方法

耐心，耐心 还是**耐心**

###标题2

* * *
路漫漫其修远兮，吾将上下而求索

####方法

经常写blog对自己是一种复习和巩固，也训练了自己将技术或者心得表达出来的能力，更重要会记录你自己的每一个脚印，记录自己的成长。`it is great treasure`

**无序列表**

* 列表1
  item1
  item2
* 列表2
    * item1
        * item3
* 列表3

**有序列表**

1. 列表1
2. 列表2
    1. item1
    2. item2
5. 列表3
6. 列表4

**代码片段**

i am code: `code wrapper`
are you funny? `funny`

**代码区段**

1) 利用一个tab制表符

    this is code area
    
2) 利用三个反引号
```python
def hello(name):
    this.name = name
    print "Hello, {0}".format(name)
```

**引用块**

>this is quote setences
>test test test test test

**链接**

1)自链接

`http://blog.csdn.net/liupc123123`
http://blog.csdn.net/liupc123123

2) 基本链接

`[liupc123123](http://blog.csdn.net/liupc123123 "liupc123123的CSDN blog.")`
[liupc123123](http://blog.csdn.net/liupc123123 "liupc123123的CSDN blog.")

3) 引用链接

`[liupc123123]`
`[liupc123123]: http://blog.csdn.net/liupc123123 "liupc123123的CSDN blog."`
[liupc123123]
`注意：对于引用链接我们最好将其统一放置在最末尾，因为markdown翻译器对于段落之间的间隙是固定的，
即使你使用多次回车，这个间隙不会变大，所以如果不放置在最末尾，可能导致下一个新的段落看起来和引用
链接所在的段落没有分开。`

**分割线**
* * *
##The End!

[liupc123123]: http://blog.csdn.net/liupc123123 "liupc123123的CSDN blog."



> # Project 1: HTML and CSS

## styleA

* 水平居中，等距间隔，考察`div`的`margin`属性，要求间距随`window`大小变化，但是`box`本身大小不变，所以可以设置`margin-top`为百分比，注意`margin-top`和`margin-bottom`只能有一个，不然间距就扩大了一倍。
* 略微复杂一点的是文字，前五个都是水平居中，最后一个还要垂直居中。
  * `text-align`属性指定文本水平对齐方式，包含`center, left, right`。
  * 垂直居中的实现方法，不依赖于其父元素，采用`flex`布局则很容易实现，`justify-content`定义在主轴上的对齐方式，`align-item`定义在交叉轴上的对齐方式。

参考：

* [Flex 布局教程：语法篇](https://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)

* [flex demo](http://static.vgee.cn/static/index.html)

## styleB



参考：

* [CSS中flex和inline-flex的区别](https://segmentfault.com/a/1190000023823917)
* [block，inline和inline-block概念和区别](https://www.cnblogs.com/keithwang/p/3139517.html)

## styleC





## XHTML check

将HTML内的数据粘贴到http://validator.w3.org/#validate_by_input+with_options内进行验证，如下结果为验证通过：

![image-20211103180127994](/Users/yzhang68/Documents/Yuqi/project/Stanford-CS-142-Web-Applications/notes/project_1_notes.assets/image-20211103180127994.png)
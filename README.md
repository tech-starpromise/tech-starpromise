# StarPromise.星许🌟

> 更多内容在➡️[`这里哦`](https://blog.star-promise.top)

- 👋 Hi, I’m @tech-starpromise
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
tech-starpromise/tech-starpromise is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

---


## EP01. Hello 2024

> “Ok, I'm online.”

Oi! 实在没想到原来这样就能有自己的个人博客了。特别感谢 [**@技术爬爬虾**](https://github.com/tech-shrimp) 和 [**@黄玄**](https://github.com/Huxpro) 两位大佬的视频和模版！

本人不过热爱技术的IT小白一个，偶然诞生了一个建个人网站分享和记录自己生活碎片和奇奇怪怪的代码的想法。于是花重金~~¥99+¥39~~买了一年的阿里云 ECS 和域名，又通宵了三天在网上扒代码看教程，翻了无数材料解决各种各样奇奇怪怪的问题，终于在 ECS 上建成了一个半成品，**But...**

~~苦于国内严格的互联网实名管制~~，实在是没有精力和时间完成网站域名的 ICP 和公安部备案。然后就是毫无意外的，star-promise.top 无法被解析到我的 ECS 上 ：）

本来想就此放弃了，但在神奇的 YouTube 上我发现了 GitHub 这个神奇的地方，了解了 GitHub Pages 这个项目，**于是！星许的第一篇 BLOG 就此诞生。**（撒花撒花🎉🎉）

这就是 **StarPromise.星许** 诞生的故事了，今后在 [**这个地方**](https://blog.star-promise.top) 我会和大家分享一些新奇好玩的所见所闻，大家多多捧场哦！

晚安！

---


## EP02. Markdown语法总结

> “Powered by [`guangqiang-liu`](https://github.com/guangqiang-liu/MarkdownSyntax)”

### 认识 Markdown

*<a name="markdown-anchor"></a>*

Markdown 是一种用来写作的轻量级「标记语言」，它用简洁的语法代替排版，而不像一般我们用的字处理软件 Word 或 Pages 有大量的排版、字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。目前来看，支持 Markdown 语法的编辑器有很多，包括很多网站（例如 BLOG ）也支持了 Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出 HTML 格式的文件用来网站发布，也可以十分方便的导出 PDF 格式。

### Markdown 的优点

* 页面内容可读性强，简洁直观。

* 纯文本，兼容性强，几乎任何文本编辑器都可打开。

* 格式转换简便，轻松的导出`.HTML`、`.PDF`、`.MD`等多种格式文件。

* 不需太过于关心页面排版，只需关注内容。

### Markdown 官方文档

* [创始人 John Gruber 的 Markdown 语法说明](https://daringfireball.net/projects/markdown/syntax)

* [Markdown 中文版语法说明](http://wowubuntu.com/markdown/#list)

### 常用的Markdown工具

![MacDown logo](/img/in-post/241202/LogoMacdown.webp)

#### MacOS平台(个人推荐使用Macdown)

在 Mac OS X 上，个人强烈建议使用 **[Macdown](https://github.com/MacDownApp/macdown)** 这款免费且十分好用的 Markdown 编辑器，它支持**实时预览**，即，左边是你编辑 Markdown 语言，右边会实时的生成预览效果。

![Macdown](/img/in-post/241202/MacdownSoftwareInterface.webp)

#### Windows平台

Windows用户建议尝试以下两款产品：

* **MarkdownPad** 

* **MarkPad**

### Markdown 语法的简要介绍

#### 换行符

在Markdown语法中，换行需要**敲两个回车键**，即在两段文本之间添加一个空行来达到换行的效果。

1. **敲一个回车键**

   *代码展示：*

   ````
   这是第一个段落
   这是第二个段落
   ````
   *效果展示：*
   
   这是第一个段落
   这是第二个段落
   
   *上面的写法在Macdown编辑器中显示是两行，但是在预览效果发现，他们还是在同一行，只是两个段落中间多出来一个空格，这时我们在两行中间多敲一个回车键就能达到换行的效果。*

2. **敲两个回车键**

   *代码展示：*
	
   ````
   这是第一个段落
   
   这是第二个段落
   ````
   
   *效果展示：*

   这是第一个段落

   
   
   这是第二个段落
   
   *有同学发现，我本来只是想让同一句话换个行显示而已，你这中间还多出来一空行，不够美观。能不能中间没有留白的空行，但是也能实现换行的效果尼？当然办法总是有的，下面就介绍第二种换行方式。*

> 官方解释：*To force a line break, put two spaces and a newline (return) at the end of the line.*

3. 在同一段落中需要换行的字符后**敲两个空格，再敲回车键**就能达到同一段落换行的效果

   *代码展示：*

   ````
   这是第一个段落  
   这是第二个段落
   ````
   
   *效果展示：*
   
   这是第一个段落  
   这是第二个段落

#### 强调

在Markdown语法中，想要着重强调某一部分内容时，可以使用`*`或者是`_`来包裹要着重强调的内容。`**`或`__`表示字体加粗，`*`或`_`表示字体斜体，（个人推荐使用`*`）

这里的内容强调分两种语法，一种是**加粗强调**，另一种是为*斜体强调*

1. 加粗（**也可以使用快捷键生成加粗符号：Command+b**）

   *代码展示：*

   ````
   **StarPromise.星许**  
   __StarPromise.星许__
   ````

   *效果展示：*

   **StarPromise.星许**  
   __StarPromise.星许__

2. 斜体（**也可以使用快捷键生成斜体符号：Command+i**）

   *代码展示：*

   ````
   *StarPromise.星许*  
   _StarPromise.星许_
   ````
   
   *效果展示：*

   *StarPromise.星许*  
   _StarPromise.星许_

#### 标题

在Markdown语法中，添加标题使用`#`，就会有标题加粗的效果出现。标题分为六个等级，即1个#代表一级标题，2个#代表二级标题，直到六级标题。

*代码展示：*

````
# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6
````

也可以使用下面的方式来设置一级、二级标题，不过不推荐使用。

*代码展示：*

````
Header 1
========

Header 2
---------
````

#### URL链接

在写自己的博客中，经常有需求要跳转到某一个网页或者邮件。这时需要使用link链接。link链接方式分为内联(Inline)和外部引用(Reference)

* Inline

  将邮箱地址包裹在<>内部，就形成了可以点击的邮箱地址: <mail@starpromise.top>

  *代码展示：*

  ````
   <mail@starpromise.top>
  ````

  将网页url包裹在<>内部，就形成了可以点击访问的网页地址: <https://blog.star-promise.top>

  *代码展示：*

  ````
  <https://blog.star-promise.top>
  ````

  自定义网页链接的标题`[标题](链接)`: [StarPromise.星许](https://blog.star-promise.top)

  *代码展示：*

  ````
  [StarPromise.星许](https://blog.star-promise.top)
  ````

* Reference (外部引用的好处可以在整个文章中重复引用网页地址或者图片地址**不需要重复拷贝同一个url**)

  *代码展示：*

  ````
  [arbitrary_id]: https://blog.star-promise.top  
  [a_link][arbitrary_id]  
  [b_link][arbitrary_id]  
  [c_link][arbitrary_id]
  ````

  *效果展示：*  

  [arbitrary_id]: https://blog.star-promise.top
  [a_link][arbitrary_id]  
  [b_link][arbitrary_id]  
  [c_link][arbitrary_id]
  
  

#### 引用图片

Markdown中引用图片资源同样也是分为内联(Inline)和外部引用(Reference)

* Inline

  *代码展示：*

  ````
  ![Alt Image Text](/img/in-post/241202/Example.webp)
  ````

  *效果展示：*

  ![Alt Image Text](/img/in-post/241202/Example.webp)

* Reference  (同上，好处也是不用重复拷贝一个链接)

  *代码展示：*

  ````
  [image-id]: https://blog.star-promise.top/img/in-post/241203/WeChat.png
  ![1][image-id]
  ![2][image-id]
  ![3][image-id]
  ````

  *效果展示：*

  [image-id]: https://blog.star-promise.top/img/in-post/241203/WeChat.png
  ![1][image-id]
  ![2][image-id]
  ![3][image-id]

#### 列表

Markdown语法中，列表分为三类：**有序列表、无序列表、嵌套列表**

* 有序列表

  ````
  1. 列表1
  2. 列表2
  3. 列表3
  ````

* 无序列表(无序列表中，`*`、`+`、`-`效果一样，**个人推荐使用`*`**)

  ````
  * 列表1
  * 列表2
  
  + 列表4
  + 列表5
  
  - 列表7
  - 列表8
  ````

* 缩进层次嵌套列表

  ````
  * 这是一个嵌套列表
    1. 列表1
    2. 列表2
    3. 列表3
  ````

#### 引用

Markdown语法中，使用`>`表示引用，引用名人名言或者是别人的一段文本等。

1. *代码展示：*

   ````
   > "三天不学习，赶不上刘少奇。" - 毛泽东 
   ````

   *效果展示：*

> "三天不学习，赶不上刘少奇。" - 毛泽东 

2. 当然引用也可以嵌套使用的

   *代码展示：*

   ````
   > 这是一级引用
   >
   > > 这是二级引用
   > >
   > > > 这是三级引用  
   > > > 还是三级引用
   
   >> 这是二级引用
   
   > 这是一级引用
   ````

   *效果展示：*

> 这是一级引用
>
> > 这是二级引用
> >
> > > 这是三级引用  
> > > 还是三级引用

>> 这是二级引用

> 这是一级引用

3. 引用也可以和其他的markdown语法混合使用

   *代码展示：*

   ````
   > `这是一级引用`
   >
   > > *这是二级引用*
   > >
   > > > * 这是三级引用  
   > > > * 还是三级引用
   > > >
   > > > 1. 还是三级标题
   > > > 2. 还是三级标题
   
   >> **二级引用**
   
   > [一级引用](https://star-promise.top)
   ````

   *效果展示：*

> `这是一级引用`
>
> > *这是二级引用*
> >
> > > * 这是三级引用  
> > > * 还是三级引用
> > >
> > > 1. 还是三级标题
> > > 1. 还是三级标题

>> **二级引用**

> [一级引用](https://star-promise.top)

#### 内嵌文本 InlineCode

- 当我们想让某一文本内容内嵌在边框内，我们可以使用一对反引号包裹内容

  *代码展示：*

  ````
  `测试文字`
  ````

  *效果展示：*

  `测试文字`

- 当文本内容中正好包含有反引号，这时需要使用空格隔开

  *代码展示：*

  ```
   ``code has `backticks` ``
  
   ```` ``Code with `backticks` `` ````
  ```

  *效果展示：*

   ``code has `backticks` ``

   ```` ``Code with `backticks` `` ````

#### 代码块 CodeBlock

三个反引号或者三个波浪号。

* *方式 1*

  ````
  ```
  code
  ```
  ````

* *方式 2*

  ```
  ~~~
  code
  ~~~
  ```

  *注意切换到英文输入法哦*~

#### 分割线

当我们想对文章的某些内容做上下分割，这时我们可以使用分割线语法，有两种表达方法：

*代码展示：*

````
***

or

---
````

*效果展示：*

***

or

---

#### 表格

表格的使用肯定我们每一位同学都不陌生，因为我们经常使用Excel表格来展示各种数据报表。很庆幸Markdown同样也支持表格制作，而且使用方式很简单。表格由行与列组成，这里只需要**注意表格的内容对齐方式**即可。

1. 没有设置对齐方式

   *代码展示：*

   ````
   First Header  | Second Header
   ------------- | -------------
   Content Cell  | Content Cell
   Content Cell  | Content Cell
   ````

   *效果展示：*

   | First Header | Second Header |
   | ------------ | ------------- |
   | Content Cell | Content Cell  |
   | Content Cell | Content Cell  |

2. 设置表格对齐

   *代码展示：*

   ````
   | Left Aligned 居左对齐 | Center Aligned 居中对齐 | Right Aligned 居右对齐 |
   | :-------------------- | :---------------------: | ---------------------: |
   | col 3 is              |     some wordy text     |                  $1600 |
   | col 2 is              |        centered         |                    $12 |
   | zebra stripes         |        are neat         |                     $1 |
   ````

   *效果展示：*

   | Left Aligned 居左对齐 | Center Aligned 居中对齐 | Right Aligned 居右对齐 |
   | :-------------------- | :---------------------: | ---------------------: |
   | col 3 is              |     some wordy text     |                  $1600 |
   | col 2 is              |        centered         |                    $12 |
   | zebra stripes         |        are neat         |                     $1 |
   
   *这里需要注意：表格的左边和右边的`|`可以省略不需要使用，表格左右两边加上`|`主要基于美观考虑，表格的对齐方式仅仅取决于`:`*

#### 锚点

在写文章时，有时候我们有这样的需求，从文章的某一个位置直接跳转到指定的另一个位置，这时使用到a标签的锚点语法。

*使用方式：*

在待跳转到的位置上添加一行：

````
<a name="markdown-anchor"></a>
````

在需要跳转处使用：

````
[`认识 Markdown`](#markdown-anchor)
````

*例如：本文中我添加到了[`认识 Markdown`](#markdown-anchor)处*

#### del标签

作用是在内容中间添加一条**删除线**

*代码展示：*

````
<del>xxx</del>

or

~~xxx~~
````

*效果展示：*

<del>xxx</del>

or

~~xxx~~

#### u标签

作用是在内容底部添加一条**横线**

*代码展示：*

````
<u>xxx</u>
````

*效果展示：*

<u>xxx</u>

#### mark标签

作用是对内容颜色进行**高亮**处理

*代码展示：*

````
<mark>xxx</mark>
````

*效果展示：*

<mark>xxx</mark>

#### font标签

作用是设置文本的**字体颜色**

*代码展示：*

````
<font color=Red>xxx</font>
````

*效果展示：*

<font color=Red>xxx</font>

### 总结

**以上内容是作者花了N小时总结出来的常用Markdown语法，介绍了Markdown的十几种常用的语法知识，并逐一的进行了效果展示。可以说足以满足读者们日常中各种使用Markdown编写文章的需求。老铁们要是感觉文章对您有帮助，请多多鼓励哦～**

*最后最重要的一点：`趁热打铁，温故知新！`*

**强烈建议读者们认真浏览作者的这篇文章后，自己使用Markdown写一篇文章，体会一下Markdown语法的优雅之处！**

---


## EP03. 我的微信公众号开通咯

> “Yeah It's online. ”

![My WeChat](/img/in-post/241203/WeChat.png)

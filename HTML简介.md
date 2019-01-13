HTML常用标签


HTML标签：标记标签通常被称为HTML标签，HTML标签是HTML语言中最基本的单位，HTML标签是HTML最重要的组成部分。

    标签不会出现在页面中，只有标签中的内容才会显示在页面上 ：也就是<html>内容</html>

    标签不区分大小写，但是推荐使用小写 ：(X)HTML 版本中强制使用小写，这样更加严谨

    标签分为闭合标签和空标签 ：闭合标签是指由开始标签和结束标签组成的一对标签，这种标签允许嵌套和承载内容，例如：<html></html>、<p></p>；空标签是没有内容的标签，在开始标签中自动闭合，例如：<img />、<br />、<hr />等

html标签分类

html标签又叫做html元素，它分为块级元素和内联元素（也可以叫做行内元素），都是html规范中的概念。

块级元素(行元素)

块级元素是指本身属性为display:block;的元素。因为它自身的特点，我们通常使用块级元素来进行大布局的搭建。

特点:

1. 独占一行，每一个块级元素都会从新的一行重新开始，从上到下排布

2. 可以直接控制宽度、高度以及盒子模型的相关css属性

3. 在不设置宽度的情况下，块级元素的宽度是它父级元素内容的宽度

4. 在不设置高度的情况下，块级元素的高度是它本身内容的高度

标签描述

div    常用块级容器，也是css layout的主要标签

p    段落、放一段文字

h1~h6    标题

h1    网页中最重要的内容：logo 网站的标题；网页中普通的标题 一般用h3或者h4、h5

ul li    每一项前面都有一个点（无序列表）

ol li    每一项前面都有对应的数字（有序列表）

dl    定义列表

dt    列表项目

dd    项目描述

table    表格

caption    表格的标题

thead    表格的头部

tbody    表格的主体

tr    行

td    列 （普通的列，可以放在tbody下面）

th    列 （只放在thead的里面，文字默认加粗）

hr    分割线

form    表单

span    通常放几个文字，或者小图标

a    超链接 自带下划线

b    加粗

strong    加粗强调

i    斜体

em    斜体强调

s    中划线（不推荐使用）

strike    中划线

del    文档中已被删除的文本

br    强制换行

u    下划线

textarea    多行文本输入框

input    输入框

select    下拉列表

labelinput     元素定义标注（标记）

img    图片

sub    下标

sup    上标

big    大字体文本

small    小字体文本

嵌套规则

块级元素div、h1~h6、address、blockquote、center、dir、dl、dt、dd、fieldset、form、hr、isindex、menu、noframes、noscript、ol、p、pre、table、ul ...

行内元素span、a、abbr、acronym、b、bdo、big、br、cite、code、dfn、em、font、i、img、input、kbd、label、q、s、samp、select、small、strike、strong、sub、sup、textarea、tt、u、var ...

块级元素与块级元素平级、内嵌元素与内嵌元素平级。

块级元素可以包含内联元素或某些块元素，但是内联元素不能包含块元素，它只能包含其他的内联元素。

有几个特殊的块级元素只能包含内联元素，不能再包含块级元素。如:h1~h6、p、dt

块级元素不能放在p标签里面。

基本标签

<html>…</html> 定义 HTML 文档

<head>…</head>      文档的信息

<meta>              HTML文档的元信息

<title>…</title>    标题

<link>              外部资源

<style>…</style>    样式信息

<body>…</body>      页面内容

<!--…-->            注释

文本标签



<b>...</b>                粗体字

<strong>...</strong>      粗体字(强调)

<i>...</i>                斜体字

<em>...</em>              斜体字(强调)

<center>…</center>        居中文本

<ul>…</ul>                无序列表

<ol>…</ol>                有序列表

<li>…</li>                列表项目

<a href=”…”>…</a>          超链接

<font>                    定义文本字体尺寸、颜色、大小

<sub>                      下标

<sup>                      上标

<br>                      换行

<p>                        段落

表格标签

  <table>…</table> 定义表格

   <th>…</th>          定义表格中的表头单元格

   <tr>…</tr>          定义表格中的行

   <td>…</td>          定义表格中的单元
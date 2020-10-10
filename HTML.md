# Hbuider快捷键

### 一、文件操作

- 新建菜单： ctrl + N
- 新建： ctrl + N
- 关闭： ctrl + w
- 全部关闭： ctrl + shift + w
- 保存： ctrl + s
- 全部保存： ctrl + shift + s
- 刷新： F5
- 属性： Alt + Enter

### 二、编辑操作

- 激活代码助手：Alt + /
- 显示方法参数提示： Alt + Shift + ?
- 撤销： Ctrl + Z
- 重做： Ctrl + Y
- 复制选区或光标所在行： Ctrl + C
- 剪切选区或光标所在行： Ctrl + X
- 粘贴： Ctrl + V
- 复制文件路径： Ctrl + Shift + C
- 改写切换： 插入
- 删除： 删除
- 删除当前行： Ctrl + D
- 删除前一词： Ctrl + Backspace
- 删除后一词： Ctrl + Delete
- 删除至行首： Shift + Backspace
- 删除至行尾： Shift + Delete
- 删除当前标签： Ctrl + Shift + T
- 安全重命名对象： Ctrl + F2
- 重命名文件： F2
- 合并下一行： Ctrl + Alt + J
- 整理代码格式： Ctrl + Shift + F
- 向上移动行： Ctrl + 向上箭头
- 向上移动行： Ctrl + 向下箭头
- 选中当前行： Ctrl + L
- 开启/关闭注释整行： Ctrl + /
- 开启/关闭注释已选内容： Ctrl + Shift + /
- 注释分隔条： Ctrl + Shift + B
- 对选中标签加包围（加P元素）： Ctrl + 9
- 去包围： Ctrl + 0
- 快速修正： Ctrl + 1

### 三、插入操作

- 向下空行： Ctrl + Enter
- 向上空行： Ctrl + Shift + Enter
- 重复插入当前行或选中区域： Ctrl + Shift + R
- 快速插入空白字符（nbsp）： Shift + 空格键
- 快速插入<script type="math/tex" id="MathJax-Element-4">
  </script> (在html中）： Shift + Enter
- 快速插入\n（在js、 css中）：Shift + Enter
- 插入HTML标签（使用当前词）： Ctrl + Shift + ，
- 切换插入方式： Ctrl + Shift + 插入
- 插入词语结尾符： Ctrl + Alt + Enter

### 四、转义操作

- 全部大写： Ctrl + Shift + X
- 全部小写： Ctrl + Shift + Y
- 首字大写： Ctrl + Shift + -
- URL转码： Ctrl + Shift + 7
- URL解码： Ctrl + Shift + 5
- 八进制转十进制： Ctrl + Shift + 0
- 十进制转八进制： Ctrl + Shift + 8
- 十六进制转十进制： Ctrl + Shift + 9
- 十进制转十六进制： Ctrl + Shift + 6

### 五、选择操作

- 全选： Ctrl + A
- 向左选词： Ctrl + Shift + 左箭头
- 向右选词： Ctrl + Shift + 右箭头
- 选择相同词： Ctrl + Shift + A
- 选择HTML父节点： Ctrl + Alt + 向上箭头
- 选前一个节点： Ctrl + Alt + 向左箭头
- 选后一个节点： Ctrl + Alt + 向右箭头
- 选所有子节点： Ctrl + Alt + 向下箭头
- 选择成对内容： Ctrl + [
- 列选择： Ctrl + Alt + C
- 块选择： Alt + Shift + A
- 选择至行首： Ctrl + 主页键
- 选择至行末： Ctrl + End

### 六、跳转操作

- 上一个选项卡： Ctrl + Tab
- 选择至行末： Ctrl + Shift + Tab
- 后退到历史文件： Alt + 左箭头
- 前进到历史文件： Alt + 右箭头
- 转到匹配的括号： Alt + [
- 转到匹配的引号： Alt + ‘
- 设置/取消书签： Ctrl + Alt + B
- 转到上一个文本输入点： Alt + 向上箭头
- 转到下一个文本输入点： Alt + 向下箭头
- 折叠： Ctrl + Alt + -
- 展开： Ctrl + Alt + /
- 转到特定行： Ctrl + G
- 激活快捷键视图： Ctrl + Shift + L
- 激活便捷大纲： Ctrl + O

### 七、查找操作

- 搜索条（查找、替换）： Ctrl + F
- 聚焦到搜索条件框内： Ctrl + Alt + F
- 聚焦到替换输入框内： Ctrl + Alt + E
- 隐藏搜索条：Esc
- 在搜索条内换行： Alt + Shift + Enter
- HTML标签规范： Ctrl + Shift + H

### 八、运行

- Ctrl + R

### 九、视图

- 活动视图或编辑最大化： Ctrl + M
- 放大字体： Ctrl + Shift + =
- 减小字体： Ctrl + -



# HTML基本结构

HTML 

Hyper Text Markup Language（超文本标记语言）

超文本包括：文字、图片、音频、视频、动画等

### 标签的语法：

```html
<html>
    <head>
        <title></title>
    </head>
</html>
```





### 标签之间的关系：

1.包含关系  (父子关系、嵌套关系)

2.并列关系  (兄弟关系)

```html
<!DOCTYPE html>
<!--文档声明标签 通常写在文档第一行-->
<html>

	<head lang="en">
		<meta charset="UTF-8">
		<!--定义文档属性-->
		<!-- UTF-8 万国码 几乎包含了任何国家的编码 -->
		<title>Just test for HTML</title>
	</head>

	<body>
		写一句话 
		
		<!-- 标题标签-->
		
		<h1>一级标题</h1>
		<h2>二级标题</h2>
		<h3>三级标题</h3>
		<h4>四级标题</h4>
		<h5>五级标题</h5>
		<h6>六级标题</h6>
		
		鹅鹅鹅，<br />
		曲项向天歌。<br /><hr />
		白毛浮绿水，
		<p>红掌破轻薄。</p>
		<hr />
		我是<strong>加粗</strong>字体
		<br />
		我也是<b>加粗</b>的
		<br /><hr />
		我是<em>斜体</em>的标签
		<br />
		我是<i>斜体</i>的标签
		
		
	</body>

</html>

```



### HTML页面的标签

```html
<!DOCTYPE  html>  文档声明标签  通常写在文档的第一行

<meta> 是定义文档属性的标签

UTF-8  万国码，包含了几乎所有国家的字符编码

<h1> ~<h6>标题标签
<br /> 换行标签
<hr /> 水平线标签
<p></p> 段落标签
<strong> <b> 加粗标签
<em> <i> 斜体标签
    
<!--注释内容-->  注释标签

```



### HTML特殊符号

| 显示 | 说明           | 实体名称 | 实体编号 |
| :--- | :------------- | :------- | :------- |
|      | 半方大的空白   | &ensp ;  | &#8194;  |
|      | 全方大的空白   | &emsp ;  | &#8195;  |
|      | 不断行的空白格 | &nbsp ;  | &#160;   |
| <    | 小于           | &lt;     | &#60;    |
| >    | 大于           | &gt;     | &#62;    |
| &    | &符号          | &amp;    | &#38;    |
| "    | 双引号         | &quot;   | &#34;    |
| ©    | 版权           | &copy;   | &#169;   |
| ®    | 已注册商标     | &reg;    | &#174;   |
| ™    | 商标（美国）   | ™        | &#8482;  |
| ×    | 乘号           | &times;  | &#215;   |
| ÷    | 除号           | &divide; | &#247;   |



### 文件路径



#### 相对路径

相对于引用它的页面的位置

```html
<img src="../2B.jpeg" />
```

..表示上一级路径

#### 绝对路径

在我们磁盘中的位置

```html
<img src="D:/2B.jpeg" />
```



### 图片标签

```html
<img src="图片的路径" alt="找不到图片时，显示该内容" title="鼠标悬停时提示内容" width="图片宽度，单位默认px" height="图片高度，单位默认px"/>
```





### < a >标签

在所有浏览器中，链接的默认外观是：

- 未被访问的链接带有下划线而且是蓝色的

- 已被访问的链接带有下划线而且是紫色的

- 活动链接带有下划线而且是红色的

  

  **当我们访问的是外部链接地址的时候，网页地址前要加http://**

语法

```html
<a href="目标位置路径" target="连接打开的窗口位置" title="鼠标悬停时提示内容">文字</a> 
```

#### target的几种属性

| 值          | 描述                                 |
| ----------- | ------------------------------------ |
| _blank      | 在新窗口中打开被链接文档。           |
| _self       | 默认。在相同的框架中打开被链接文档。 |
| _parent     | 在父框架集中打开被链接文档。         |
| _top        | 在整个窗口中打开被链接文档。         |
| *framename* | 在指定的框架中打开被链接文档。       |



#### 锚链接

锚点(anchor)：其实就是超链接的一种，一种特殊的超链接

 普通的超链接，

```html
<a href="路径"></a> 
```

是跳转到不同的页面

 而锚点，

```html
<a href="路径"></a>
```

 可以在同一个页面中不同的位置间跳转

 可以看到，跳转到锚点的超链接跟普通的超链接格式是一样的，

##### 1.使用锚点的步骤：

   1.1.先建立锚点目标，
        如上所述，锚点可以在同一页面的不同位置间跳转，其实就是在元素间跳转，
		常用的场景就是，页面很长，让用户方便在页面不同部分间跳转
		建立锚点目标，只需要给目标元素增加id或者name即可，推荐id：

   1.2.要创建跳转到id="test"的div的锚点， 

```html
<a href="#test"></a>
```

**注意：1.锚点的超链接路径一定包含"#",而后面紧跟元素的id或者name(所以id和name必须一样，其实我试了有时name是不生效的)**

##### 2.锚点使用总结：

  2.1. 建立锚点的元素必须要有id或name属性，最好两个都有
  2.2. 锚点超链接一定包含井号"#",锚点超链接都在链接的最末端，具体看后面例子
  2.3. 同一个页面不同部分的跳转，锚点的写法   

```html
目标元素：<p id="test"></p>     锚点超链接：<a href="#test"></a>
```

  2.4. 不同页面跳转，同时存在锚点

```html
    目标元素：a.html页面的<div id="test"/>   锚点超链接：<a href="a.html#test"></a>
```

​		（先跳到a.html页面，然后再寻找id=test的元素）

### 块元素和行内元素

#### 块元素

无论内容多少都独占一行

常见的块元素

```html
<address>、<center>、<h1>~<h6>、<hr>、<p>、<pre>、<ul>、<ol>、<dl>、<table>、<div>、<form>
```



#### 行内元素

内容撑开宽度，左右都是行内元素的可以排在一行

常见的行内元素：

```html
<span>、<a>、<br>、<b>、<strong>、<img>、<input>、<textarea>、<select>、<sup>、<sub>、<em>、<del>
```



##### 行内元素与块级元素的区别：

1.行内元素与块级元素直观上的区别二、行内元素与块级元素的三个区别

  行内元素会在一条直线上排列（默认宽度只与内容有关），都是同一行的，水平方向排列。

  块级元素各占据一行（默认宽度是它本身父容器的100%（和父元素的宽度一致），与内容无关），垂直方向排列。块级元素从新行开始，结束接着一个断行。

2.块级元素可以包含行内元素和块级元素。行内元素不能包含块级元素，只能包含文本或者其它行内元素。

3.行内元素与块级元素属性的不同，主要是盒模型属性上：行内元素设置width无效，height无效(可以设置line-height)，margin上下无效，padding上下无效





# 列表、表格与媒体元素



### 无序列表

无序列表是一个项目的列表，此列项目使用粗体圆点（典型的小黑圆圈）进行标记。

无序列表始于 <ul> 标签。每个列表项始于 <li>。

```html
<ul>
<li>Coffee</li>
<li>Milk</li>
</ul>
```



不同类型的无序列表

```html
<html>
<body>

<h4>Disc 项目符号列表：</h4>
<ul type="disc">
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ul>  

<h4>Circle 项目符号列表：</h4>
<ul type="circle">
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ul>  

<h4>Square 项目符号列表：</h4>
<ul type="square">
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ul>  

</body>
</html>
```



### 有序列表

同样，有序列表也是一列项目，列表项目使用数字进行标记。

有序列表始于 <ol> 标签。每个列表项始于 <li> 标签。

```html
<ol>
<li>Coffee</li>
<li>Milk</li>
</ol>
```



不同类型的有序列表

```html
<html>
<body>

<h4>数字列表：</h4>
<ol>
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ol>  

<h4>字母列表：</h4>
<ol type="A">
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ol>  

<h4>小写字母列表：</h4>
<ol type="a">
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ol>  

<h4>罗马字母列表：</h4>
<ol type="I">
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ol>  

<h4>小写罗马字母列表：</h4>
<ol type="i">
 <li>苹果</li>
 <li>香蕉</li>
 <li>柠檬</li>
 <li>桔子</li>
</ol>  

</body>
</html>
```



### 定义列表

自定义列表不仅仅是一列项目，而是项目及其注释的组合。

自定义列表以 <dl> 标签开始。每个自定义列表项以 <dt> 开始。每个自定义列表项的定义以 <dd> 开始。

```html
<dl>
<dt>Coffee</dt>
<dd>Black hot drink</dd>
<dt>Milk</dt>
<dd>White cold drink</dd>
</dl>
```



定义列表

```html
<html>
<body>

<h2>一个定义列表：</h2>
<dl>
   <dt>计算机</dt>
   <dd>用来计算的仪器 ... ...</dd>
   <dt>显示器</dt>
   <dd>以视觉方式显示信息的装置 ... ...</dd>
</dl>

</body>
</html>
```



### 嵌套列表

```html
<html>
<body>

<h4>一个嵌套列表：</h4>
<ul>
  <li>咖啡</li>
  <li>茶
    <ul>
    <li>红茶</li>
    <li>绿茶</li>
    </ul>
  </li>
  <li>牛奶</li>
</ul>

</body>
</html>
```



```html
<html>
<body>

<h4>一个嵌套列表：</h4>
<ul>
  <li>咖啡</li>
  <li>茶
    <ul>
    <li>红茶</li>
    <li>绿茶
      <ul>
      <li>中国茶</li>
      <li>非洲茶</li>
      </ul>
    </li>
    </ul>
  </li>
  <li>牛奶</li>
</ul>

</body>
</html>
```



#### 注意

```html
<ul>标签、<ol>标签他们的子标签只能是<li>标签
<li>标签是块标签

```



### 表格

#### 定义和用法

<table> 标签定义 HTML 表格。

简单的 HTML 表格由 table 元素以及一个或多个 tr、th 或 td 元素组成。

| 标签 | 作用                   |
| ---- | ---------------------- |
| tr   | 定义表格行             |
| th   | 定义表头，默认居中加粗 |
| td   | 义表格单元             |



```html
<table border="1">
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
</table>
```



#### 表格属性

| 属性        | 值                                                | 描述                                               | 备注                    |
| :---------- | :------------------------------------------------ | :------------------------------------------------- | ----------------------- |
| align       | left center right                                 | 规定表格相对周围元素的水平对齐方式。               | 也可以在<tr><tr/>中使用 |
| Valign      | top middle bottom                                 | 规定表格相对周围元素的垂直对齐方式。               | 也可以在<tr><tr/>中使用 |
| bgcolor     | rgb(x,x,x)  **#xxxxxx** colornam                  | 规定表格的背景颜色。                               |                         |
| border      | pixels                                            | 规定表格边框的宽度。数值的大小向内影响外边框的大小 |                         |
| cellpadding | pixels%                                           | 规定单元边沿与其内容之间的空白。会撑开表格大小     |                         |
| cellspacing | pixels%                                           | 规定单元格之间的空白。不会撑开表格大小             |                         |
| frame       | void abov ebelow hsides lhs rhs vsides box border | 规定外侧边框的哪个部分是可见的。                   |                         |
| rules       | none groups rows cols all                         | 规定内侧边框的哪个部分是可见的。                   |                         |
| summary     | *text*                                            | 规定表格的摘要。                                   |                         |
| width       | *%pixels*                                         | 规定表格边框的宽度。                               |                         |



### video 标签

#### 定义和用法

```html
<video> 标签定义视频，比如电影片段或其他视频流。
目前，<video> 元素支持三种视频格式：MP4、WebM、Ogg
```

#### 属性

| 属性     | 值                 | 描述                                                         |
| :------- | :----------------- | :----------------------------------------------------------- |
| autoplay | autoplay           | 如果出现该属性，则视频在就绪后马上播放。                     |
| controls | controls           | 如果出现该属性，则向用户显示控件，比如播放按钮。             |
| height   | *pixels*           | 设置视频播放器的高度。                                       |
| loop     | loop               | 如果出现该属性，则当媒介文件完成播放后再次开始播放。         |
| muted    | muted              | 如果出现该属性，视频的音频输出为静音。                       |
| poster   | *URL*              | 规定视频正在下载时显示的图像，直到用户点击播放按钮。         |
| preload  | auto metadata none | 如果出现该属性，则视频在页面加载时进行加载，并预备播放。如果使用 "autoplay"，则忽略该属性。 |
| src      | *URL*              | 要播放的视频的 URL。                                         |
| width    | *pixels*           | 设置视频播放器的宽度。                                       |
| controls | controls           | 控制插件的播放状态                                           |



### audio 标签

#### 定义和用法

```html
<audio> 标签定义声音，比如音乐或其他音频流。
目前，<audio> 元素支持的3种文件格式：MP3、Wav、Ogg。
```

#### 属性

| 属性     | 值                 | 描述                                                        |
| :------- | :----------------- | :---------------------------------------------------------- |
| autoplay | autoplay           | 如果出现该属性，则音频在就绪后马上播放。                    |
| controls | controls           | 如果出现该属性，则向用户显示音频控件（比如播放/暂停按钮）。 |
| loop     | loop               | 如果出现该属性，则每当音频结束时重新开始播放。              |
| muted    | muted              | 如果出现该属性，则音频输出为静音。                          |
| preload  | auto metadata none | 规定当网页加载时，音频是否默认被加载以及如何被加载。        |
| src      | *URL*              | 规定音频文件的 URL。                                        |



### source 标签

#### 定义和用法

```
<source> 标签为媒介元素（比如 <video> 和 <audio>）定义媒介资源。
将音频/视频以不同的格式放入该标签中，浏览器会自动播放
<source> 标签允许您规定可替换的视频/音频文件供浏览器根据它对媒体类型或者编解码器的支持进行选择。
```

#### 属性

| 属性  | 值              | 描述                       |
| :---- | :-------------- | :------------------------- |
| media | *media query*   | 规定媒体资源的类型。       |
| src   | *url*           | 规定媒体文件的 URL。       |
| type  | *numeric value* | 规定媒体资源的 MIME 类型。 |





###  iframe标签

#### 标签定义及使用说明

```html
<iframe> 标签规定一个内联框架。
一个内联框架被用来在当前 HTML 文档中嵌入另一个文档。
    
给标签先定义一个name属性
在超链接中的target目标指向name
```



| 属性     | 值                                                           | 描述                                       |
| :------- | :----------------------------------------------------------- | :----------------------------------------- |
| height   | *pixels*                                                     | 规定 <iframe> 的高度。                     |
| name     | *name*                                                       | 规定 <iframe> 的名称。                     |
| sandbox  | "" allow-forms allow-same-origin allow-scripts allow-top-navigation | 对 <iframe> 的内容定义一系列额外的限制。   |
| seamless | seamless                                                     | 规定 <iframe> 看起来像是父文档中的一部分。 |
| src      | *URL*                                                        | 规定在 <iframe> 中显示的文档的 URL。       |
| srcdoc   | *HTML_code*                                                  | 规定页面中的 HTML 内容显示在 <iframe> 中。 |
| width    | *pixels*                                                     | 规定 <iframe> 的宽度。                     |



### href和src的区别

虽然一直在用这两个属性，但是一直没有具体的去区分和了解这两个属性的区别，今天就来看看

**href**标识超文本引用，用在**link**和**a**等元素上，**href**是引用和页面关联，是在当前元素和引用资源之间建立联系

**src**表示引用资源，表示替换当前元素，用在**img**，**script**，**iframe**上，src是页面内容不可缺少的一部分。

**src**是source的缩写，是指向外部资源的位置，指向的内部会迁入到文档中当前标签所在的位置；在请求**src**资源时会将其指向的资源下载并应用到当前文档中，例如js脚本，img图片和frame等元素。

<script src="js.js"></script>当浏览器解析到这一句的时候会暂停其他资源的下载和处理，直至将该资源加载，编译，执行完毕，图片和框架等元素也是如此，类似于该元素所指向的资源嵌套如当前标签内，这也是为什么要把js饭再底部而不是头部。

<link href="common.css" rel="stylesheet"/>当浏览器解析到这一句的时候会识别该文档为css文件，会下载并且不会停止对当前文档的处理，这也是为什么建议使用link方式来加载css而不是使用@import。

 

补充：link和@import的区别

两者都是外部引用CSS的方式，但是存在一定的区别：

区别1：link是XHTML标签，除了加载CSS外，还可以定义RSS等其他事务；@import属于CSS范畴，只能加载CSS。

区别2：link引用CSS时，在页面载入时同时加载；@import需要页面网页完全载入以后加载。

区别3：link是XHTML标签，无兼容问题；@import是在CSS2.1提出的，低版本的浏览器不支持。

区别4：ink支持使用Javascript控制DOM去改变样式；而@import不支持。
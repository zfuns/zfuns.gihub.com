title: markdown test
date: 2017-03-02
categories: 测试
tags: test
---
该文章用于展示markdown生成的格式。


# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

#### 标题（用底线的形式）Heading (underline)

This is an H1
=============

This is an H2
-------------

### 字符效果和横线等
                
----

~~删除线~~ 

<s>删除线（开启识别HTML标签时）</s>

*斜体字*      _斜体字_
**粗体**  __粗体__
***粗斜体*** ___粗斜体___

上标：X<sub>2</sub>，下标：O<sup>2</sup>

**缩写(同HTML的abbr标签)**

> 即更长的单词或短语的缩写形式，前提是开启识别HTML标签时，已默认开启

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.

### 引用 Blockquotes

> 引用文本 Blockquotes

引用的行内混合 Blockquotes
                    
> 引用：如果想要插入空白换行`即<br />标签`，在插入处先键入两个以上的空格然后回车即可，[普通链接](http://localhost/)。

### 锚点与链接 Links

[普通链接](http://localhost/)

[普通链接带标题](http://localhost/ "普通链接带标题")

直接链接：<https://github.com>

[锚点链接][anchor-id] 

[anchor-id]: http://www.this-anchor-link.com/

GFM a-tail link @pandao

> @pandao

### 多语言代码高亮 Codes

#### 行内代码 Inline code

执行命令：`npm install marked`

#### 缩进风格

即缩进四个空格，也做为实现类似`<pre>`预格式化文本(Preformatted Text)的功能。

    <?php
        echo "Hello world!";
    ?>
    
预格式化文本：

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

### 图片 Images

图片加链接 (Image + Link)：

![]( {{ site.mobile-hp | prepend: site.baseurl }} )

> 图为：我的头像
                
----

### 列表 Lists

#### 无序列表（减号）Unordered Lists (-)
                
- 列表一
- 列表二
- 列表三
     
#### 无序列表（星号）Unordered Lists (*)

* 列表一
* 列表二
* 列表三

#### 无序列表（加号和嵌套）Unordered Lists (+)
                
+ 列表一
+ 列表二
    + 列表二-1
    + 列表二-2
    + 列表二-3
+ 列表三
    * 列表一
    * 列表二
    * 列表三

#### 有序列表 Ordered Lists (-)
                
1. 第一行
2. 第二行
3. 第三行
          
----
                    
### 绘制表格 Tables

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机      | $1600   |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |
                    
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell 

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Display the help window.       |
| `destroy()`   | **Destroy your computer!**     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |
                
----

#### 特殊符号 HTML Entities Codes

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot; 

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

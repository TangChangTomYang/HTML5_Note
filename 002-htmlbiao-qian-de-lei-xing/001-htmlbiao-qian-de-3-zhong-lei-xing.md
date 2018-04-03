

####一、块级标签

特点：
- 1 独占一行的标签。
- 2 能随时修改标签的高度和宽度（主要有： div \p \h1\ Ul \li）。

```objc
div{
    background-color: red;
    width: 70%;
    height: 200px;
}

<!--块级标签  独占一行，可以随时设置宽度和高度-->
<div>我是 块级标签div 独占一行 随时设置宽度</div>

```

####二、行内标签（内联标签）
特点：
- 1、多个标签可以显示在同一行。
- 2、行内标签的宽度和高度由内容的多少决定，不能随意修改。（主要有： span \ button）。

```objc
行内标签 不能随时设置 宽度和高度
a{
    width: 200px;
    height: 150px;
}

行内标签 多个行内标签能显示在同一行 行内标签的尺寸由 内容的多少决定，不能修改
<span> 我是行内标签 span</span>
<a href="#"> 我 是行内 超链接标签 </a>
<label> 我行内label 标签</label>

<span> 我是行内标签 span</span>
<a href="#"> 我 是行内 超链接标签 </a>
<label> 我行内label 标签</label>

<span> 我是行内标签 span</span>
<a href="#"> 我 是行内 超链接标签 </a>
<label> 我行内label 标签</label>
```






####一、伪类选择器

|属性|描述|
|-|-|
|:active|向被激活的元素添加样式|
|:focus|向拥有键盘输入焦点的元素添加样式|
|:hover|当鼠标悬浮在元素的上方时,向元素添加样式|
|:link|向未被访问的连接添加样式|
|:visited|向已被访问的连接添加样式|
|:first-child|向元素的第一个子元素添加样式|
|:lang|向带有指定 lang 属性的元素添加样式|

- 1> :focus 选择器（选中选择器）

```objc

/*伪类选择器*/
/*伪类的使用步骤:
 1> 拿到对应的标签
 2> 在对应的标签后面写对应的伪类即可
 3> 在伪类的代码中写入对应的 样式描述即可
 */
/*focus 选中的意思*/
input:focus{
    /*1 取出外边线*/
outline: none;
    /*2 修改边框的颜色*/
border: 1px solid blue;
    /*修改边框大小*/
width: 200px;
height: 80px;
    background-color: purple;
color: red;




<input type="我是输入框"; placeholder="占位文字">
<input class="abc" type="text"; placeholder="我是类 输入框">

```

***

- 2> :hover  悬浮伪类选择器


```objc
/*abb 类 悬浮选择*/
.abb:hover{
    background-color: blue;
}

/*伪类选择器， 选择的目标是 div 里的 abb 类*/
/*悬浮 效果*/
div.abb:hover{
    background-color: orange;
}

<div class="abb"> wo shi rongqi</div>
<p class="abb"> 我是 段落 </p>

<input type="我是输入框"; placeholder="占位文字">
<input class="abc" type="text"; placeholder="我是类 输入框">

```





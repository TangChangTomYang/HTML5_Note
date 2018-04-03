####一、CSS 布局  position
- absolute: 生成绝对定位的元素，相对于Static 定位以外的第一个父元素进行定位。
元素的位置通过 left right top bottom 属性进行规定。

- fixed: 生成绝对定位的元素，相对于浏览器窗口进行定位。
元素的位置通过 left right top bottom 属性进行规定。

- relative: 生成相对定位的元素，相对于其正常位置进行定位。
因此，left:20 会向元素的左边添加20像素

- Static： 默认值，没有定位，元素出现在正常的流中（忽略 top bottom left right 或者 z-index 声明）

- inherit: 规定应该从父亲元素继承position属性的值。


**一旦，设置了position 标签就变成了 行内-块级标签了**


####二、 定位子标签的要点
**子 绝  父  相**

```objc
.test1{
    width: 300px;
    height: 300px;
    background-color: red;
    
    position: relative; /*要定位子控件，父控件中的位置必须这样写*/
}

.test2{
    width: 50px;
    height: 50px;
    /*设置圆角*/
    border-radius: 25px;
    background-color: cyan;
    /* 父标签的position 只要不是static 就可以了，但是做好是absolute*/
    position:absolute ; /*定位子控件，子控件中必须这样写*/
    /*left: 5px;*/
    /*top: 3px;*/

    /*right: 0px;*/
    /*bottom: 0px;*/

    /*居中显示*/
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%); /*向左 向上 各平移自身宽度 高度的 50%*/
}

.test3{

    background-color: blue;
}

.test4{

    background-color:  purple;
    /*相对于浏览器定位,注意相对于浏览器就没有父控件了*/
    position: fixed;
    top: 10px;
}

<div class="test1">

    <div class="test2"></div>
    <div class="test3">fdsgasdglasjdgf;lsafglasglasdgal</div>

</div>

```














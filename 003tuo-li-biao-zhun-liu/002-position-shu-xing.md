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
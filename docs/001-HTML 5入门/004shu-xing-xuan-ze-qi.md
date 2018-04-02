####一、属性选择器

**说明:**
在HTML 的每个标签中可以有多个 **自定义属性**,如:

```objc
<div age="23" name="rose">age name </div>
```

- 1> 通过属性名 找到对应的标签, 有该属性的标签全部能用.

```objc

div[name]{
    color: red;
}

可以作用于下面的所有标签
<div name="rose">我是容器</div>
<div age="23" name="rose">age name </div>
<div name="rose" age="18">我是容器 name age </div>
<div name="rose" age="19">我是容器name age</div>
<div name="rose" age="20">我是容器name age</div>

```


- 2> 找到属性名满足某个条件的标签,如下:

```objc

div[name = "rose"]{
    color: orange;
}

只能作用于下面name="rose"的所有标签 
<div name="rose">我是容器</div>
<div age="23" name="rose">age name </div>
<div name="rose" age="18">我是容器 name age </div>
<div name="rose" age="19">我是容器name age</div>
<div name="rose" age="20">我是容器name age</div>

```

- 3> 通过多级属性名找到 多维属性

只有第一 第一级是 name 属性, 二级是age 的标签才会生效
```objc
div[name][age]{
    color: blue;
}

<div name="rose">我是容器</div>
<div age="23" name="rose">age name </div>
<div name="rose" age="18">我是容器 name age </div>
<div name="rose" age="19">我是容器name age</div>
<div name="rose" age="20">我是容器name age</div>

```
















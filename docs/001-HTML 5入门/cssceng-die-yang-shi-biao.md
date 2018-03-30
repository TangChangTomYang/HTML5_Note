

###一 什么是CSS?
- **CSS 全称Cascading Style Sheets,层叠样式表,他用来控制HTML标签的样式,在美化网页的过程中起到重要的作用.**

- **CSS 有三种书写形式**
    - 1> 行内样式(内联样式),直接在标签的Style属性中书写,作用于对应的标签内部,每个标签内部都有一个style 属性,如下: 
    ```objc
    <div style="background-color: red; color: white; font-size: 30px">我是容器标签</div>
    ```
    - 2> 页内样式, 在本网页的Style 标签中书写, style 属性卸载 Head 头部标签里面
    ```objc
    <style>
        body{
            color: red;
        }
    </style>
    ```
    其实上面这种写法和下面这种写法是等价的
    ```objc
    <body style="color: red;"> </body>
    ```
    
    - 3> 外部样式:在单独的CSS 文件中书写,然后在网页中用link 标签引用,如下:
    ```objc
    <link rel="stylesheet" href="index.css">
 
    ```
    rel 是relationship 关系的意思, href 是引用的文件,shang上面,这个引用关系可以这样理解, 引用的资源地址是"index.css" 引用的关系是 "stylesheet",表示引用的文件作为层叠样
    
    
    
- **CSS 内Style属性有单值 属性 和复合属性**
    - 单值属性, 一个属性对应多个值
    ```objc
    <div style="background-color: red; color: white; font-size: 30px">我是容器标签</div>
    ```
    - 复合属性, 一个属性对应多个值
    ```objc
    <p style="border: 5px solid blue; border-radius: 10px ; font-size: 20px">我是段落标签</p>

    ```
    
    
    
   
** CSS 页内样式** 
```objc

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>

    <!--页内样式,作用于整个页面-->
    <!--选择器,拿到页面内的所有的body 标签-->
    <style>
    /**/
    /*选择器,拿到页面内的所有的body 标签*/
    body{
        background-color: green;
    color: white;
    }

    /*选择器,拿到页面内的所有的p 标签*/

    p{
        
        background-color: red;
    border: 5px dashed red;
    }


    </style>

</head>

    <body>

        <div>我是容器标签</div>
        <div>我是容器标签</div>
        <div>我是容器标签</div>

        <p>我是段落标签</p>
        <p>我是段落标签</p>

    </body>

</html>

```
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    

####一、并列选择器

写法： 多个选择器之间使用 ， 间隔，属性写在 {} 中，如下
```objc
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Title</title>

        <style>
        
        并列选择器
        .abc,#ppp{
            color: orange;
        }

        div,p{
            color: red;
        }
        </style>
    </head>
    <body>

        <div>我是容器</div>
        <p>我是p 标签</p>

        <div  class="abc">我是容器22222</div>
        <p id="ppp">我是p 标签22222</p>


    </body>
</html>
```
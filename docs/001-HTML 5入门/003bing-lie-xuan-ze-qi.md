####一、并列选择器

写法： 多个选择器之间使用 ， 间隔，属性写在 {} 中，描述的是某几类标签，只要包含的都满足，如下
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


####二、复合选择器 （是有且关系）
写法： 标签选择器 + 类名 ，描述的某一具体类的标签
```objc
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Title</title>

        <style>

            div.divclass{
            color: purple;
            }
        </style>
    </head>
    <body>
        <divclass="divclass">
            我是div 里面的  divclass
        </div>

        <div>
            我是div 里面的
        </div>

    </body>
</html>
```


####三、后代选择器（满足后代条件的标签都满足 ）
写法：描述的是 某个标签里的某种标签，具体写法如下：
```objc
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Title</title>

        <style>

        /*后代选择器，选择某个标签里面的所有标签*/
        div a {
        color: red;
            
        }

        </style>
    </head>
    <body>

        <div>
        <p>

        <a href="#">我是div 里面的a 标签 孙子</a>
        </p>
        <a href="#">我是div 里面的a 标签 儿子</a>
        </div>

        <a href="#">我是超链接</a>
    </body>
</html>
```


####四、 直接后代选择器（只有满足直接后代条件的标签才满足）
写法： 如下，
```objc
<!DOCTYPE html>
<html lang="en">
    <head>
    <meta charset="UTF-8">
        <title>Title</title>

        <style>

        /*直接后代选择器，选择直接的后代*/
        /*只选择 div 里 p 标签里面的 a */
        div p >a{
            color: red;
            
        }

        a{
            color: black;
        }
        </style>
    </head>
    <body>

        <div> <p><a href="#">我是直接的后代</a></p></div>
        <div> <a href="#">我是后代</a></div>

    </body>
</html>

```

####五、 相邻兄弟选择器，只作用于相邻的标签
写法：如下
```objc
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Title</title>

        <style>

            /* 相邻兄弟选择器，只作用于相邻的标签*/
            div + p{
                color: red;
            }
        </style>
    </head>
    <body>


        <div>我是容器</div>
        <div>我是容器</div>
        <div>我是容器</div>
        <div>我是容器</div>
        <div>我是容器</div>
        <p> 我是相邻段落</p>
        <p> 我是段落</p>
        <p> 我是段落</p>
        <p> 我是段落</p>
        <p> 我是段落</p>


    </body>
</html>


```



















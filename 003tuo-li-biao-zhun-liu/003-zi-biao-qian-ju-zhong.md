


```objc
#test1{
    background-color: red;
    width: 300px;
    height: 300px;

    /*让子标签和内容居中 所有的子标签居中*/
    /*通过这种方式不能让块级标签居中，只能让块级标签的内容居中*/
    text-align: center;
}

span{
    background-color:  purple;
}

.btnClass{
    width: 100px;
    height: 50px;
}

div{
    background-color: orange;
    width: 150px;

    /*块级标签居中*/
    margin-left: auto;
    margin-right: auto;

    /*也可以下面这种写法*/
    /*margin: 0 auto;*/
}


<div id="test1">

    <!-- 行内标签 -->

    <span> 行内</span>

    <!--行内块级标签-->
    <!--<button> 我 是按钮 行内块级标签</button>-->
    <!--<button> 我 是按钮 行内块级标签</button>-->
    <!--<button> 我 是按钮 行内块级标签</button>-->
    <!--<button class="btnClass"> 我 是按钮 行内块级标签</button>-->
    <!--<button> 我 是按钮 行内块级标签</button>-->
    <!--<button> 我 是按钮 行内块级标签</button>-->
    <!--<button> 我 是按钮 行内块级标签</button>-->
    <!--<button> 我 是按钮 行内块级标签</button>-->
    <!--<button> 我 是按钮 行内块级标签</button>-->

    <!--块级标签-->
    <div>我是 块级标签</div>

</div>

```
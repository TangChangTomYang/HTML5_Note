

####一、盒子模型 

**不同的浏览器盒子模型是不一样的，目前主要非为2种浏览器，IE 浏览器和非IE浏览器**

- IE 浏览器盒子模型
![](/assets/ie box.png)


- 非IE浏览器盒子模型
![](/assets/none ie box.png)




#### 解决盒子模型不一致的问题
为了解决不同浏览器采用不同的盒子模型，我们在HTML 中加入盒子模型的设置如下

```objc
/*设置盒子的模式*/
box-sizing: border-box; /* 盒子的尺寸从 border 开始计算， 默认情况下IE使用的是这种*/
/*box-sizing: content-box; !* 盒子的尺寸从 内容开始计算*!*/
```





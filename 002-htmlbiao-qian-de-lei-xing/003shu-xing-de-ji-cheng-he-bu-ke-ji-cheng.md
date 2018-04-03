#### 一、属性的继承和不可继承
**CSS 有N多属性，根据继承性，主要分为2大类：**
- **1、可继承属性：**
  - 父标签的属性值会传递给子标签
  - 一般是**文字控制**属性
  
  示例如下：
```objc
因为字体是继承的，所以下面的所有的标签都应用 .test 中的样式
  
  .test {
    
    font-size: 60px;
    color: red;
    font-family: "Apple Chancery";
  }
```
 
- **2、不可继承属性：**
  - 父标签的属性值不会传递给子标签
  - 一般是**区块控制**属性
  
  
  
  
  
  ##CSS 常用属性 （粗体可继承）
  
  - 所有标签可继承
      
      **visibility**、**cursor**
      
  - 内联标签可继承
  letter-spacing、word-spacing、white-spacing、**line-height**、**color**、**font** 、
  **font-family**、**font-size**、font-style、font-variant、 **font-weight**、**text-decoration**、text-transform、direction
  
  - 块级标签可继承
  **text-indent**、**text-align**
  
  - 列标签可继承
  **list-style**、list-style-type、list-style-position、list-style-image
  
  
  
  
  
  

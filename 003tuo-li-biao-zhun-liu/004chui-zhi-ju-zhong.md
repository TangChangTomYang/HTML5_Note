#### 垂直居中

- 行内标签、行内块级标签垂直居中，在父控件中设置line-height = height (即设置行高为自己的高度)，也可也在自己里面设置line-height = 父控件的行高。

- 块级标签垂直居中，设置line-height = height 后高度会变化和父控件一样高，内容居中，如果子控件的高度和父控件的高度不一样需要设置垂直居中，那么需要定位

           父控件中写： position:relative
           子控件中写： position:absolute
                      top:50%
                      left:50%
                      transform:translate(-50%,-50%)
                      
                      
                      



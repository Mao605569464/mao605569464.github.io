#  Web前端俱乐部
关注我的微信公众号（扫描下面的二维码或搜索 wushengzhekou）  
![烟雨风飘渺](http://www.1990tu.com/i/20170616142631qqx.jpeg)

##   CSS的语法:  
*   CSS的定义是由三个部分构成:  
    *  选择符(selector)，  
    *  属性(properties)  
    *  属性的取值(value)。  
    
####  语法:  
```
　　selector {property: value}   
　　(选择符 {属性:值})
```  
####  说明：
   一般是你要定义样式的HTML标记，  
   例如:body、p、table……，  
   你可以通过此方法定义它的属性和值，  
   属性和值要用冒号隔开:  

```
 　例子:
   body {color: black}， 
```  
      此例的效果是使页面中的文字为黑色。   
      如果属性的值是多个单词组成，  
      必须在值上加引号，  
      比如字体的名称经常是几个单词的组合:     
```
　  例子:  
    p {font-family: "sans serif"}  
    (定义段落字体为sans serif)
```  
   如果需要对一个选择符指定多个属性时，    
   我们使用分号将所有的属性和值分开:   

```
   例子:  
   p {text-align: center; color: red}  
   段落居中排列;并且段落中的文字为红色)  
```  
####  选择符组  
   你可以把相同属性和值的选择符组合起来书写，  
   用逗号将选择符分开，  
   这样可以减少样式重复定义:   

```
   h1, h2, h3, h4, h5, h6 { color: green }    ·
```  
   (这个组里包括所有的标题元素，每个标题元素的文字都为绿色)  
```  
   p, table{ font-size: 9pt }  
 ```  
   (段落和表格里的文字尺寸为9号字)     
#####  效果完全等效于:  

```  
   p { font-size: 9pt }
   table { font-size: 9pt }
```  
####  类选择符  
　　用类选择符你能够把相同的元素分类定义不同的样式，   
    定义类选择符时，在自定类的名称前面加一个点号。  
    假如你想要两个不同的段落，一个段落向右对齐，  
    一个段落居中，你可以先定义两个类:  
    
```  
    p.right {text-align: right}
　　p.center {text-align: center}
```  
　　然后用不在不同的段落里，  
　　只要在HTML标记里加入你定义的class参数:   
```  
   这个段落向右对齐的
   这个段落是居中排列的
```    
#####  类选择符还有一种用法，  
　　在选择符中省略HTML标记名，  
　　这样可以把几个不同的元素定义成相同的样式:   
  
```  
　.center {text-align: center} 
 (定义.center的类选择符为文字居中排列)
```  
##  这里我也给大家分享了一些自己录制的教程和自己写的一些学习资料  
链接：http://pan.baidu.com/s/1dERvlaL 密码：2yq6  

如果有问题也可以到QQ群咨询我  

[加入QQ群](http://shang.qq.com/wpa/qunwpa?idkey=7778213778b4e241a0f361e0339e91195c30ea9bff36fa9e040be091b0f3ecd0)

也可以关注微信公众号问我，我都会知无不言言无不尽的。  


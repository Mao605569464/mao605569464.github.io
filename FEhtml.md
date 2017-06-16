#  Web前端俱乐部

关注我的微信公众号（扫描下面的二维码或搜索 wushengzhekou）  

![烟雨风飘渺](https://mmbiz.qlogo.cn/mmbiz_png/m4AoHibicE9ctiaMc8WKzXWaT9ekBHByLeia8oq7oUVv49eYDF6IGVdOl9AWCjD7ib3DrQSicSABB5TZFwCiaTUOFrdkA/0?wx_fmt=png)

###  什么是 HTML？  
HTML 是用来描述网页的一种语言。  
HTML 指的是超文本标记语言 (Hyper Text Markup Language)  
HTML 不是一种编程语言，而是一种标记语言 (markup language)  
标记语言是一套标记标签 (markup tag)  
HTML 使用标记标签来描述网页  

###  HTML 标签  
HTML 标记标签通常被称为 HTML 标签 (HTML tag)。  
  +  HTML 标签是由**尖括号**包围的关键词，比如&lt;html&gt;  
  -  HTML 标签通常是**成对出现**的，比如 &lt;b&gt; 和 &lt;/b&gt;  
  - 标签对中的第一个标签是**开始标签**，第二个标签是**结束标签**  
  -  开始和结束标签也被称为**开放标签**和**闭合标签**  
  
###  HTML 文档 = 网页  
  -  HTML 文档**描述网页**  
  -  HTML 文档**包含 HTML 标签**和纯文本  
  -  HTML 文档也被称为**网页**  
  
##  这里我也给大家分享了一些自己录制的教程和自己写的一些学习资料  
>    链接：http://pan.baidu.com/s/1dERvlaL 密码：2yq6  
如果有问题也可以到QQ群咨询我  
/****************
*
* 发起添加群流程。群号：Web前端俱乐部(280832773) 的 key 为： 0to6IpxKHwGKrJ07vkH_CiAkAErEMlON
* 调用 joinQQGroup(0to6IpxKHwGKrJ07vkH_CiAkAErEMlON) 即可发起手Q客户端申请加群 Web前端俱乐部(280832773)
*
* @param key 由官网生成的key
* @return 返回true表示呼起手Q成功，返回fals表示呼起失败
******************/
public boolean joinQQGroup(String key) {
    Intent intent = new Intent();
    intent.setData(Uri.parse("mqqopensdkapi://bizAgent/qm/qr?url=http%3A%2F%2Fqm.qq.com%2Fcgi-bin%2Fqm%2Fqr%3Ffrom%3Dapp%26p%3Dandroid%26k%3D" + key));
   // 此Flag可根据具体产品需要自定义，如设置，则在加群界面按返回，返回手Q主界面，不设置，按返回会返回到呼起产品界面    //intent.addFlags(Intent.FLAG_ACTIVITY_NEW_TASK)
    try {
        startActivity(intent);
        return true;
    } catch (Exception e) {
        // 未安装手Q或安装的版本不支持
        return false;
    }
}

也可以关注微信公众号问我，我都会知无不言言无不尽的。

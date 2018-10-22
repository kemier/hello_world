`linux` `网络编程` `socket` `epoll`  
欢迎到访  
很高兴见到您  
祝您，早上好，中午好，下午好，晚安  
*斜体1*  
_斜体2_  
**粗体1**  
__粗体2__  
这是 一个 ~~删除线~~  
***粗斜体1***  
___粗斜体 2___
**~~粗斜体删除线1~~**  
~~***粗斜体删除线2***~~  
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")  

链接
------
### 链接外部URL  

|#|语法|效果|  
|---|----|-----|  
|1|`[我的博客](http://blog.csdn.net/guodongxiaren "悬停显示")`|[我的博客](http://blog.csdn.net/guodongxiaren "悬停显示")|  
|2|`[我的知乎][zhihu] `|[我的知乎][zhihu] |  
  
语法2由两部分组成:  
- 第一部分使用两个中括号，[ ]里的标识符（本例中zhihu），可以是数字，字母等的组合，标识符上下对应就行了（**姑且称之为URL标识符**)  
- 第二部分标记实际URL。  
  
>使用URL标识符能达到复用的目的，一般把全文所有的URL标识符统一放在文章末尾，这样看起来比较干净。  
>>URL标识符是我起的名字，不知道是否准确。囧。。  
  
### 链接本仓库里的URL  
  
|语法|效果|  
|----|-----|  
|`[我的简介](/example/profile.md)`|[我的简介](/example/profile.md)|  
|`[example](./example)`|[example](./example)|  
  
### 图片链接  
给图片加链接的本质是混合图片显示语法和普通的链接语法。普通的链接中[ ]内部是链接要显示的文本，而图片链接[ ]里面则是要显示的图片。  
直接混合两种语法当然可以，但是十分啰嗦，为此我们可以使用URL标识符的形式。  
  
|#|语法|效果|  
|---|----|:---:|  
|1|`[![weibo-logo]](http://weibo.com/linpiaochen)`|[![weibo-logo]](http://weibo.com/linpiaochen)|  
|2|`[![](/img/zhihu.png "我的知乎，欢迎关注")][zhihu]`|[![](/img/zhihu.png "我的知乎，欢迎关注")][zhihu]|  
|3|`[![csdn-logo]][csdn]`|[![](/img/csdn.png "我的csdn,欢迎关注!")[csdn]|  
  
因为图片本身和链接本身都支持URL标识符的形式，所以图片链接也可以很简洁（见例3）。  
注意，此时鼠标悬停时显示的文字是图片的title，而非链接本身的title了。  
> 本文URL标识符都放置于文末  


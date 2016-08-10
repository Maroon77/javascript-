# 字符串
### slice()、substring()、substr()对比：
- stringObject.slice(start,end)
- stringObject.substring(start,end)
- stringObject.substr(start,length)

String对象的方法slice()、substring()、substr()都可以返回字符串的指定部分。slice()比substring()要灵活，它允许使用负数作为参数。slice()与substr()不同，它用两个字符的**位置**来指定子串，而substr()用**字符位置和长度**来指定子串。

String.slice()和Array.slice()类似，都是从字符串/数组里返回start到end之间的字符或者数组。
    
# window对象
- window.opener.location.reload()
- window.location.reload()

# 数组
### splice
##### 向数组中添加或者删除元素，返回被删除的元素
array.splice(index,howmany,item1,......,itemn);
- index:必填，规定添加/删除元素的位置，从0开始。可以为负数
- howmany：必填，要删除的元素的数目，如果为0，则不会删除元素
- item1...itemn:选填，向数组添加的新元素

# image对象

# 浏览器缓存
浏览器缓存是浏览器端保存数据用于快速读取或避免重复资源请求的优化机制，加速网页的展示。浏览器端缓存的机制分为9种。
* http缓存
* websql
* indexDB
* cookies
* **localstorage**
* sessionstorage
* application cache
* cacheStorage
* flash缓存

### cookies(html存储出现之前):
#### http请求头上会带着，大小4k，主域名污染

### html5本地存储
#### localstorage&&sessionstorage
##### ls永久存储，除非手动删除；ss是在浏览器关闭时删除；大小为5M，存储形式为key-value.IE8+支持
##### getItem() setItem() removeItem() key() clear()
##### 可以存储数组、json数据、图片、脚本、样式文件等(数组、json等必须转换成字符串存储：stringify)
##### 好处：利用本地存储，减少网络传输；弱网络环境下，高延迟，低带宽，尽量把数据本地化。

### html5离线缓存
application cache




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






一、字符串
1、slice()、substring()、substr()对比：
    stringObject.slice(start,end)
    stringObject.substring(start,end)
    stringObject.substr(start,length)
    String对象的方法slice()、substring()、substr()都可以返回字符串的指定部分。Slice()比substring()要灵活，它允许使用负数作为参数。slice()与substr()不同，它用两个字符的位置来指定子串，而substr()用字符位置和长度来指定子串。
    PS：String.slice()和Array.slice()类似，都是从字符串/数组里返回start到end之间的字符或者数组。

---
title: "C/C++常用数据类型对应字节数"
layout: post
date: 2016-04-1 10:26
tag: C/C++
blog: true
star: true

---
## content:
 
{% highlight raw %}
-（1）16位平台  
char         1个字节8位  
short        2个字节16位  
int          2个字节16位  
long         4个字节32位  
指针          2个字节16位
{% endhighlight %}   

{% highlight raw %}
-（2）32位平台  
char         1个字节8位  
short        2个字节16位  
int          4个字节32位  
long         4个字节32位  
long long    8个字节64位   
指针          4个字节32位  
{% endhighlight %} 

{% highlight raw %}
-（3）64位平台  
char         1个字节  
short        2个字节  
int          4个字节   
long         8个字节（区别）  
long long    8个字节  
指针          8个字节（区别）
{% endhighlight %} 
## methods方法绑定this


问题一:为什么不能使用箭头函数(官方文档有给出解释) ?

问题二:不使用箭头函数的情况下, this到底指向的是什么?

![image-20211202010652125](/Users/wo/Library/Application Support/typora-user-images/image-20211202010652125.png)

### 我们在methods中要使用data返回对象中的数据：

那么这个this是必须有值的，并且应该可以通过this获取到data返回对象中的数据。 

### 那么我们]这个this能不能是window呢？

不可以是window，因为window中我们无法获取到data返回对象中的数据；

但是如果我们使用箭头函数，那么这个this就会是window了；

### **为什么是window呢？**

这里涉及到箭头函数使用this的查找规则，它会在自己的上层作用于中来查找this； 

最终刚好找到的是script作用于中的this，所以就是window； 



this的绑定规则:https://mp.weixin.qq.com/s/hYm0JgBI25grNG_2sCRlTA


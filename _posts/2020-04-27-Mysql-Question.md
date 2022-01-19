---
layout: post
title:  "Mysql Question Introduction"
date:   2020-04-22 
categories: Python3  Django 
---
Mysql-Question Description：
   发票系统数据库：一条发票信息链接有购买方和销售方的信息


---


```
 面向对象的核心： 封装、继承、多态，这是
下面是详细阐述：
```
--



```python
class Solution(object):
    def getLeastNumbers(self, arr, k):
        """
        :type arr: List[int]
        :type k: int
        :rtype: List[int]
        """
        new_arr = []
        if k != 0 :
            if k <= len(arr):
                for i in range(0,k):
                    x = min(arr)
                    new_arr.append(x)
                    arr.remove(x)
   
                return new_arr
        else:
                return  new_arr
```
炫酷解法：
```python
   arr.sort()
   return arr[:k]
        
```


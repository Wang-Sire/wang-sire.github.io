---
layout: post
title:  "OOP - Introduction"
date:   2020-04-22 
categories: Python3  Django 
---
Mysql-Question Description：
   数据库构建 Q&A


---


```
业务场景：
实现功能：

预计需要功能：

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


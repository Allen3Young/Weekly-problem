#!/usr/bin/env python
# -*- coding: utf-8 -*-
# @Date    : 2016-02-16 15:30:27
# @Author  : Allen Young (allenyoung717@gmail.com)
# @Version : $Id$

def function(x,l):    
    l.sort() # 将list从小到大排序    
    s = 0       # 初始化和   
    n = 0       # 初始化个数
    for item in l:
        s += item   # 以金额从小到大累加
        if s > x:   # 判断是否超出所有的钱
            break
        n += 1
    return n

# 测试
x = 5 
l = [3,8,1,2,3]
print 'The output should be 2, the function return:', function(x, l)

x = 3
l = [2,1,5]
print 'The output should be 2, the function return:', function(x, l)

x = 10
l = [1,1,1,1,2,5]
print 'The output should be 5, the function return:', function(x, l)

x = 10 
l = [5,10,3,2]
print 'The output should be 3, the function return:', function(x, l)

x = 2
l = [3,8,10]
print 'The output should be 0, the function return:', function(x, l)

---
layout:     post
title:      "数据可视化实战"
subtitle:   "微博数据可视化"
date:       2017-06-12 12:00:00
author:     "MIYO"
header-img: "img/post-bg-js-module.jpg"
header-mask: 0.3
catalog:    true
tags:
    - Data visualization
    - Design
    - Python
---


> 实验来源于课堂的某个练习。数据已爬取，本实验主要在于数据的可视化并进行分析。

## 一、数据处理
对微博转发量进行排序，从而能摘取转发数量较多或中等的微博ID进行分析
```html
/Users/Miyo/Desktop/entertainment_7.txt |grep'^RL'|sort|uniq-c|sort-rn|more
```

## 二、编写运行代码
python文件：
```html
# -*- coding: utf-8 -*-
import numpy as np
file_in=open('/Users/Miyo/Desktop/entertainment_7.txt','r')
file_out=open('/Users/Miyo/Desktop/user.txt','w')
j=0 
source=""
target=""
count = 0
sign = 0
for line in file_in.readlines():
    if(line.strip()=="!!"):
        j=0
    if(j==1):
        if(line.strip() != "RL2VgHww"): 
            #j=j+1
            sign = 1#1
        else:
            sign = 0
            count = count + 1
    if(j==2):
        target = line.strip()[2:]
    if(j==12):
        source = line.strip()[2:]
        #file_out.write(source+"->"+target+"\n")
        #if(source != "PI0"):#PD0
        #    file_out.write("  " + source+"->"+target+"\n")
        if(sign == 0):
            #if(source!="0"):
            file_out.write("  " + source+"->"+target+"\n")
    j=j+1
print count
file_out.close()
file_in.close()
```

graphviz文件：
```html
digraph show {
  layout = "twopi"
  bgcolor = "#f2f1ee"
  node[shape="circle" color="white" distortion=.1 width=.1 style=filled fillcolor="#3176c4" label=""]
  edge[color="#95aed8" style="filled" arrowsize=0.3]
```

## 三、可视化分析
所有微博的转发关系示意图
![21.png](https://i.loli.net/2017/07/30/597dbbf49bcab.png)
超级大V（第一转发量）转发关系示意图
![23.png](https://i.loli.net/2017/07/30/597dbbf44cdab.png)

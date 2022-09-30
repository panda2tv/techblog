---
title: "1stop site build"
date: 2022-09-16T19:44:38+08:00
---

1 github 创建新的private repo 1stopnewsitecode; clone 到本地D:\hugo\site目录下,为本地hugo代码目录；  
2 github 创建新的private repo 1stopnewsitecodedeploy.io; clone 到本地D:\hugo\site目录下，为生成的静态deploy文件目录；
3 在本地hugo代码目录下创建新站点1stopnewsitecodedeploy.io； hugo new site 1stopnewsitecodedeploy.io
4 安装hugo theme [Syna](https://github.com/okkur/syna)
5 放弃theme Syna， 发现这个theme无法在本地打开，各种调试，还跑到作者repo去提了个issue，人家也没搭理咱，及时止损放弃。具体原因及教训看[这里]。  

---
title: "git操作要求输入用户名和密码问题"
date: 2022-09-16T17:01:07+08:00
---

根据[youtuber Ryan Schachte作者教程](https://www.youtube.com/watch?v=LIFvgrRxdt4&t=27s&ab_channel=RyanSchachte)搭建git开发环境；  
问题一：  
使用git push老是碰到：Username for 'https://github.com': 
即使把SSH key加入到github也重复要求输入；

解决: 删除本地目录，使用SSH git clone重新下载；  

问题二：  
误删/改 .git文件夹下面文件,于是只好重新删掉所有开发目录重新clone.  
务必不要手动修改/删除.git目录下所有东西，否则会破坏repo  

问题三：  
git submodule add -b main url.git public  
fatal: 'hugositebuildingblog/public' already exists and is not a valid git repo  
解决：  
要先把public 目录删掉，让git自己创建此目录
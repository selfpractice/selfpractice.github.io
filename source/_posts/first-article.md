---
title: 使用github+node.js+hexo建立我的博客
date: 2016-12-28 14:52:19
tags:

---

## 一、在github上注册账号。
直到开通并在浏览器中输入成功，以我的博客为例，输入https://selfpractice.github.io,成功显示无错误，这一部分不再赘述。

## 二、下载node.js,安装，重新启动电脑，win10可能不需要重新启动，win7一定是要的。

## 三、 安装windows for github
## 四、安装hexo
git同步后，在同步的目录下运行powershell，以我的博客为例，同步的目录在e:\myblog\selfpractice.github.io,在这个目录下运行
1) npm install hexo-cli -g
2) hexo init
3) hexo g
4) hexo s
在浏览器中输入localhost:4000，正常显示，ok

## 五、克隆主题
$ git clone https://github.com/wuchong/jacman.git themes/jacman

## 六、添加新的文章
hexo new "文章名字"
文章保存在 source\_posts 目录下

## 参考
http://www.jianshu.com/p/05289a4bc8b2 ，简书上的这篇文章可以作为参考，写的不错。




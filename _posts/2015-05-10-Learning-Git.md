---
layout: post
title:  Git学习整理
date:   2015-06-10
summary:
categories:
---

创建新仓库：创建文件夹，进入后执行`git init`  
链接仓库: `git remote add origin git@github.com:HarmonyHu/harmonyhu.github.io.git`
查看仓库：`git remote -v`
检出仓库：`git clone git@github.com:HarmonyHu/harmonyhu.github.io.git`  
提交修改到暂存目录：`git add <filename>` `git add *` `git add -A`  
提交修改到工作目录：`git commit -m "提交说明“· ·git commit -a -m "提交说明"`  
更新修改到仓库：`git push orgin master`

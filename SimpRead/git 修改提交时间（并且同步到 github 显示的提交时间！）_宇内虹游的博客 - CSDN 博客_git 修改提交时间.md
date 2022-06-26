> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/weixin_39278265/article/details/120238699)

### 文章目录

*   *   [前言](#_4)
    *   [问题描述](#_12)
    *   [解决方案](#_29)
    *   [错误尝试](#_48)
    *   [小结](#_63)
    *   [参考文献](#_70)

前言
--

创作开始时间：2021 年 9 月 11 日 15:44:56

有时候论文提交时对应的 repo 需要放在 github 上，这个时候不小心漏了一个 commit，补上的话时间戳会很尴尬，所以需要对 commit date 进行修改，这里给出解决方案。

问题描述
----

我有一个 repo，只有一个 commit：

```
Author: xxx
Date:   Mon Sep 2 16:21:24 2021 +0800

    Make all artifacts of our study available.
```

但是过了几天后，我发现有一个材料忘记提交了。。。尬住

所以需要：  
1）先补上这个提交材料  
2）修改 commit 时间，使其仍然保持原来的 Mon Sep 2 16:21:24 2021 +0800 时间。

解决方案
----

1）补上提交材料：

```
git add .
git commit --amend --no-edit
```

2）修改 commit 提交时间：

```
GIT_COMMITTER_DATE="Mon Sep 2 16:21:24 2021 +0800" git commit --amend --date "Mon Sep 2 16:21:24 2021 +0800"
git commit --amend --date "Mon Sep 2 16:21:24 2021 +0800"
```

3）同步到 github 仓库

```
git push origin master
```

错误尝试
----

只运行：

```
git commit --amend --date "<date>"
```

而没有运行：

```
GIT_COMMITTER_DATE="<date>" git commit --amend --date "<date>"
```

是根本改不了 github 上的显示时间的。

小结
--

以上。

创作结束时间：2021 年 9 月 13 日 09:48:15

参考文献
----

*   How to add a file to the last commit in git? [duplicate] [https://stackoverflow.com/questions/40503417/how-to-add-a-file-to-the-last-commit-in-git](https://stackoverflow.com/questions/40503417/how-to-add-a-file-to-the-last-commit-in-git)
*   Changing a commit date info [https://gist.github.com/ythecombinator/7e70d7baea74305c93e6](https://gist.github.com/ythecombinator/7e70d7baea74305c93e6)
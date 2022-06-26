> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [ajtl.github.io](https://ajtl.github.io/post/git_commit_manager/)

> 规范的进行 Git 提交有助于团队的开发管理。

Chapter 1 简介
------------

规范的进行 Git 提交有助于团队的开发管理。

符合规范的提交内容也能通过自动化脚本自动生成 changlog。

Chapter 2 准备工作
--------------

1.  安装 [Git](https://git-scm.com/)
2.  安装 [Node.Js](https://nodejs.org/)[1](#fn:1)

Chapter 3 提交格式
--------------

每一个提交都由 **header**(标题)、**body**(内容) 和 **footer**(页脚) 组成。其中 **header** 还包括了 _type_ 、_scope_ 和 _subject_，如下图所示：

```
<type>(<scope>): <subject>
<BLANK-LINE>

<body>
<BLANK-LINE>
<footer>
```

### 标题部分: _type_、_scope_、_subject_

#### _type_ 必需

type 表示提交类别，比如是修复一个 bug 还是增加一个新的 feature。

<table><thead><tr><th></th><th></th></tr></thead><tbody><tr><td>feat</td><td>添加新特性</td></tr><tr><td>fix</td><td>修复漏洞</td></tr><tr><td>docs</td><td>仅仅修改了文档，比如 README, CHANGELOG, CONTRIBUTE 等等</td></tr><tr><td>style</td><td>仅仅修改了空格、格式缩进、逗号等等，不改变代码逻辑</td></tr><tr><td>refactor</td><td>代码重构，没有加新功能或者修复漏洞</td></tr><tr><td>perf</td><td>优化相关，比如提升性能、体验</td></tr><tr><td>test</td><td>增加测试用例，包括单元测试、集成测试等</td></tr><tr><td>chore</td><td>改变构建流程、或者增加依赖库、工具等</td></tr><tr><td>revert</td><td>回滚到之前某一版本</td></tr></tbody></table>

#### _scope_ 可选

scope 表示修改范围，建议填写影响的功能模块。

#### _subject_ 必需

subject 表示标题内容，是对提交的简短描述，不超过 50 个字符。 最好遵循

*   以动词开头，使用第一人称现在时，比如 `change`，而不是 `changed` 或 `changes`
*   首字母不要大写
*   结尾不用句号

### 内容部分: _body_ 可选

body 表示主体描述内容，是对 subject 里内容的展开，在此做更加详尽的描述，内容里应该包含修改动机和修改前后的对比，可以多行。

footer 表示页脚，主要放置`BREAKING CHANGE`和 `Issue` 关闭的信息.

1.  BREAKING CHANGE
    
    > 格式：以 BREAKING CHANGE 开头，后面是对变动的描述、以及变动理由和迁移方法。
    
    ```
    BREAKING CHANGE: xxxxxx
    
    Before:
    xxx
    
    After:
    xxx
    ```
    
2.  Close Issue
    

### 特殊情况

#### revert

当撤销上次提交时，必须使用`revert`，后面跟着被撤销提交的标题部分。 内容部分是固定的，必须写成`This reverts commit <hash>`。其中`<hash>`是被撤销的提交 sha 标识符。 示例：

```
Closes <issue-number>
```

更多关于提交格式的资料都可以在[🌐 这里](https://www.conventionalcommits.org/)找到。

Chapter 4 配置
------------

### commitizen

[commitizen](https://github.com/commitizen) 是 是一款标准化 `git commit` 信息的工具。 `commitizen` 被设计用于更好的阅读和强制性的进行规范化的提交。除此之外，规范化的提交有助于利用过往的提交进行一些其他的分析和操作，比如可以自动化的生成 `chenglog`。

```
revert: fix: fix a bug

This reverts commit 1234567812345678.
```

安装完成后，提交时使用 `git cz` 或者`cz` 就可以替代 `git commit`。还可以使用 `git-cz`，他是`cz`的别称。

#### 适配器

`commitizen` 支持不同适配器的扩展 。这里使用 `cz-conventional-changelog` 。

```
npm install -g commitizen
```

#### package.json

打开生成的`package.json`，补全配置：

```
npm install -g cz-conventional-changelog
```

在 bash 中输入 `git cz` /`cz` / `git-cz`:

```
npm init -y
```

####  Share!
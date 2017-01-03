title: Stroyboards 的种种讨论以及它的更好的替代选择
date: 2016-12-15 17:05:30
tags:
  - iOS
  - 译文
categories:
  - iOS
---

# 原文地址

[Arkadiusz Holko 的博客](http://holko.pl/2016/03/29/storyboards-and-alternatives/)

--------------

似乎每个新建的 iOS 项目，开发者问的第一个问题都是

> 我们要用 storyboard 和 XIBs 还是全部手写整个 UI 代码？

这通常很难回答。因为选择是多种多样的即使在一个训练有素、配合极佳的团队中。然而执行一致的 UI 开发流直接导致了项目质量的高与否。

这一类的决策需要团队仔细权衡所有可用的解决方案。本文会讨论一些主流的处理 UI 开发流的方式，来帮助你选择一个适合你们团队目标的方式。

<!--more-->

# 1. Storyboards

在 iOS 开发中，storyboard 到底是是什么呢？以下是苹果官方的解释：

>A file that contains a visual representation of the app’s UI (user interface), showing screens of content and the transitions between them, that you work on in Interface Builder.

当你通过 `iOS -> Application` 的任何模板创建一个新的工程，你都将在你的工程里发现一个 `Main.storyboard` 文件。这代表苹果非常建议我们在整个工程中使用 storyboard，但是我们真的应该屈服这种说法将其使用在所有情况下吗？

我们来看看支持者与不支持者两方看法。

#### 支持者
##### 适合初学者

和我的很多同辈一样，我学习 iOS 是从斯坦福大学免费提供的 [CS193P](http://web.stanford.edu/class/cs193p/cgi-bin/drupal/) iOS 开发课程开始的。 


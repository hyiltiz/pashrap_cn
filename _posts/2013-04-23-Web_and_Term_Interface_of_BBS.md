---
layout: post
title: BBS的网页和Term界面中用户体验对比
categories: [software, BBS]
tags: [software, BBS, comparison, UX]
---

pashrap, use as a template.


网站及其可用性
========

这是为了工程心理学的关于Human Factors的一个小报告准备的提纲，先挂上来主要用来填充空空的页面。
可用性的几个维度：

 - Learnability: How easy is it for users to accomplish basic tasks the first time they encounter the design?
 - Efficiency: Once users have learned the design, how quickly can they perform tasks?
 - Memorability: When users return to the design after a period of not using it, how easily can they re establish proficiency?
 - Errors: How many errors do users make, how severe are these errors, and how easily can they recover from the errors?
 - Satisfaction: How pleasant is it to use the design?


信息提供性网站的一些优化:

 - 鉴于用户的需求、知识背景、学习能力进行优化，提高可用性
 - 复杂又重复机械操作由后端完成，给用户只看结果
 - 要有适当的学习途径
 - 犯错误的代价要小



BBS 界面的不足之处
=================

Web 界面
-----------

Web 界面虽然 *美观* ， *易于学习* 使用，
但是有很多具体的不方便之处，具体有：

 - 点击 *刷新* 后回到主页
 - 点击 *返回* 后也回到主页
 - *站内* 信不能自动保存已发送信
 - 版面的列表导航（ *分类讨论区* 不容易找到）
 - *全文搜索* 功能很差劲

![Web BBS][web]

Term 界面
--------

Term 界面提供丰富的 *快捷键* ，简化很多操作，能够 *快速浏览*
并且提供 *标题搜索* 和 *内容搜索* ，根据 *作者分类* 
等好的功能，但是也存在很多问题，犹如：

 - 没有明显突出的地址栏以 *输入bdwm.net* !
 - 主页面没有明确的 *导航*
 - *新手教程* 难以找到
 - 快捷键过多，其 *帮助页面* 也很乱
 - 不支持 *鼠标点击* 
 - *超链接* 无法直接打开
 - 浏览图片不方便
 - *上传* 附件/图片过程很复杂
 - *更改* 已经发布的帖子不方便


![Term BBS][term]

对BBS 界面的建议
===============

Web 界面
-------

 - 收藏特定的版块
 - 增强搜索功能
 - 提供已经的快捷方式
 - 还有其他同学所说的～


Term 界面
--------

 - 支持 *鼠标* 点击！
 - 提供新手教程/培训
 - *主要* 快捷键用 *通用* 快捷键（如浏览器Chrome等）
 - 整理快捷键的 *帮助* 页面
 - 支持 *图像* 浏览
 - 支持 *上传* 附件
 - **美观**


 > 一个小建议: 我觉得并行的标签和分层没有很大必要，因为其实标签式浏览
和搜索没有很大区别了。

[web]: /media/image/Web.png
[term]: /media/image/Term.png

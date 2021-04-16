---
title: "How It Works Vol.0 - 序言"
# date: 2020-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["#HowItWorks"]
author: "Chi Hsia"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "How does it work?"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

写一个「探究日常生活中各种技术的原理」的系列的想法其实在寒假的时候就有，当时寄希望于科协的同学们能写出来，但是开学之后并没有落实。最近在和朋友吃饭的时候常常会以「话说，……是怎么实现的」开头，感觉对话的过程很有意思，而且十分享受于用自己（浅薄的）专业知识解决问题的过程，于是做这个系列的念头就又死灰复燃了——这次自己写。

新买了一台相机后会希望出门乱拍，拿着扳手就想要到处找螺丝拧拧，学了新的知识却不在生活中验证是很可惜的（甚至是可悲的）。我还记得在高中的时候搭公车时会分析转弯的时候的动力学方程、非惯性参考系下如何如何、身体应该怎么倾斜、这样倾斜提供了如何的分量云云。那种解决问题的过程是一种完全不同于「解题」的体验，是一场「大脑按摩」。但是这几年的大学生活中却好久没有感受到那种舒畅的快感了。也希望能够借这个系列来锻炼自己、解放思维。

下面是挖的各种坑，只是先把各种想到的觉得有意思的东西放在这。

| 题目                 | 备注                                                         |
| -------------------- | ------------------------------------------------------------ |
| 《明日方舟》抓包分析 | 多个客户端同时连接是怎么解决冲突的？哪些操作需要访问服务器？…… |
| 《明日方舟》解包分析 | 解包一般是                                                   |
| 多人游戏如何进行联机 | 之前能够运用的网络知识都是基于TCP的（比如Socket、HTTP等），对于 UDP 如何处理丢包、P2P 连接是什么等等没有概念，借此机会学习一波。 |
| 游戏加速器的原理     | 感觉这部分会分成两个部分：游戏为什么会卡顿以及游戏加速器为什么可以解决这种卡顿现象。 |
|                      |                                                              |


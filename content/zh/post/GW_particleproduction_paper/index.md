---
title: '一种引力波的新的产生方式：bubble碰撞产生粒子'
summary: '新论文介绍：相变bubble的碰撞可以产生新粒子，从而成为新的引力波源。'
author: admin
tags:
  - grativational wave
  - electroweak phase transition
  - phase transition
  - 物理
  - 新物理探测
  - 宇宙学
  - 引力波
  - 电弱相变
  - 宇宙学相变
  - bubble
date: '2025-01-23'
reading_time: true
# Optional external URL for project (replaces project detail page).
external_link: ''
share: false
image:
   focal_point:
   preview_only: true

# links:
#   - icon: paperclip
#     icon_pack: fab
#     name: 
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

今天介绍一下去年底出现在arXiv上的一篇文章，来自约翰霍普金斯大学、东京大学、DESY的理论物理组的合作成果。

{{< figure src="image/1.png" caption="[Gravitational Waves from Particles Produced from Bubble Collisions in First-Order Phase Transitions](https://arxiv.org/abs/2412.17912)" attr="" attrlink="" >}}

标题其实就说的很清楚了，但是有几个关键词，不是专门做这个的朋友可能不熟悉。

我先来解释最关键的：first-order phase transition，也即一阶相变。

相变其实是个很广阔的词。我们平时熟悉的固液相变、气液相变，都是一阶相变，特点是两相分界明确。与此相反，如果一个相变是连续相变，没有明确的界限，就叫二阶相变。日常生活中二阶相变的例子并不是很好找，但很多本科级别的课程都会提到铁磁相变，这就是一个二阶相变。

宇宙学里面也有相变。比如我们知道现在的粒子都通过与希格斯粒子的相互作用获得质量。但是宇宙学早期，这些质量并不存在，希格斯粒子和其他粒子一样都是无质量的。随着宇宙逐渐冷却，温度降低，到了临界温度之后，质量才会产生。这个过程也属于相变，叫电弱相变。

{{< figure src="image/2.png" width="600" caption="图片来自arXiv:hep-ph/0609145">}}

这个相变具体是一阶还是二阶，目前没有直接证据。虽然标准模型下算出来是二阶，但是因为不排除有新粒子的存在，而这些新粒子可能会把相变变成一阶，因此一阶相变还是可能的。哪怕标准模型的电弱相变是二阶，宇宙学早期也很有可能存在机制类似的相变，而他们可能是一阶的。

如果是一阶，就会出现上图这样的情景。粒子们的质量从0变为一个具体的数，发生相变，并且存在明确的边界。这个明确的边界是一阶相变区别于二阶相变的典型特征。

这些边界圈起来的区域，叫做bubble。bubble内部是已经完成相变的部分，外部未完成。

这个bubble会像墙一样，可以碰撞周围的粒子，也可以和其他的bubble碰撞。读者可以把bubble想象成一个物理实体。

随着相变进行，更多的区域变成有质量的区域，bubble随之膨胀。膨胀过程中可能会碰到其他的bubble，就会产生碰撞。

正如现实世界中两个铁球碰撞产生声波一样，这些bubble的碰撞会产生引力波。

关于引力波来源的一般规律，已经有相对明确的答案。通俗讲，来源于宇宙中能量-动量张量对各向同性的偏移。

如果宇宙绝对均匀，能量和动量就是各向同性、均匀分布的。但宇宙中存在各种各样的扰动，比如本文中的bubble。这些扰动改变了能量分布，可能会使得能量分布不再各向同性。这些非各向同性的能量分布会产生引力波，这是爱因斯坦场方程的直接结论。

以上结论具体在bubble的语境下，引力波的来源一般被认为是以下三种。

第一部分是bubble本身的形变。

bubble本身是一个“质量壳”。这个壳是带有能量的。在bubble不碰撞的时候，自身是不断膨胀的规则球体，本身也是各向同性，不会产生引力波。

但碰撞会改变壳的形状，比如上图中有几个圈子已经融为一体，交叉的那部分壳消失了。这一部分的扰动不是各向同性
的，就会产生引力波。

参考：[Gravitational waves from bubble collisions: analytic derivation](https://arxiv.org/abs/1605.01403)

第二部分是bubble碰撞后的声波扰动。

早期宇宙并非真空，而是高温高密度的粒子形成的流体物质。流体作为声波介质，遇到这种bubble的扰动，自然会形成声波。

这里需要注意的是，如果单纯是bubble膨胀产生的声波，那么由于bubble是标准球体，因此声波也是各向同性，不会产生引力波。这里的关键依然是bubble碰撞了之后，声波也不再均匀。因此引力波会由这些不均匀的声波产生。

参考：[Sound shell model for acoustic gravitational wave production at a first-order phase transition in the early Universe](https://arxiv.org/abs/1608.04735)

第三部分是人类目前知之甚少的MHD turbulence。我对此了解甚浅，只知道这些扰动由剩余的声波产生，还希望能看到更多大神们的详细解释。在此就不过多赘述。

这三种在过去十几年里一直被认为是相变bubble产生引力波的全部方式。但这篇文章提出了一个新的观点：bubble之间碰撞会产生粒子，这些粒子携带的能量分布也是非各向同性的，这也会产生引力波。

之前关于bubble碰撞产生粒子的论述不少。前文提过，读者可以把bubble想象成实体。bubble相遇时，就像对撞机一样，可以碰撞出各种粒子。bubble携带的能量越大，就越能造出更重、携带能量更多的粒子。这一点在去年初的一篇文章里有过论述。[Nonthermal Heavy Dark Matter from a First-Order Phase Transition](https://arxiv.org/abs/2403.03252v1)

{{< figure src="featured.png" width="700" caption="图片来自本文介绍的文章 http://arxiv.org/abs/2412.17912" >}}

很显然的，由于碰撞本身已经破坏了各向同性，这些产生的粒子携带的能量在宇宙中必然不是各向同性的，因此会产生引力波。这便是一种之前从未被关注过的引力波来源。

下一个问题则是：bubble的能量足够大么？真的可以产生足够多的带有足够能量的粒子去产生引力波么？

对于这个问题，这篇文章也是基于大家普遍的认识：只有在真空或近乎真空的环境下产生的bubble wall才会达到如此高的能量。在有plasma出现的情况下，大部分相变潜热会被plasma带走，bubble shell携带的能量比例会很低。这个条件和之前提到的bubble collision条件类似（废话，这里的particle production就是基于bubble collision）。

于是我们将讨论分为两类：真空或近乎真空、以及有plasma的环境。前者是这篇文章的适用范围、以及bubble collision产生足够强的引力波信号的条件，一般会在supercooling下出现，或者在由一些低温环境下的量子隧穿主导的相变下出现。后者与此文无关。

于是，在此等环境下，这类新的引力波产生机制会把引力波的频谱修改为如下结果：

{{< figure src="image/3.png" width="700">}}

虚线是原本的bubble collision的结果，实线是新的产生机制的结果(最后总的结果应该为这两者相加)。可以看到在低频区，这种新的引力波产生机制大大提升了引力波的强度。

我目前还没有来得及仔细检查全部的计算，但是目前看应该没有问题。这应该是一篇意义很重大的文章，从此所有真空/类真空中产生bubble的物理过程都会用到这个结果。
# 技术调研的模式

技术调研，是一个程序员的基础能力。快速进行技术调研，是一个高级程序员的基础能力。又快又好的技术调研，是一个咨询师的核心竞争力——你永远得**比客户快半步**。

## 为什么需要技术调研

在过去美好光景里， 作为一个开发人员，又或者是一个 Tech Lead，我们并不需要在新的技术上操心——只需要看看市场的主流风向，就可以找到适合自己的技术栈。从某种意义上来说，也是热闹驱动编程的一种。

可到了今天，新技术，出现的频率越来越高；新概念，出现的时间也越来越短。作为一个开发人员，打开一个开发者相关的网站 ，我们都有可能看到一些新的技术，一些人为创造的新概念。也因此，我们可能会混淆各种各样的概念。这也就意味着，我们需要一系列的方法，来帮助我们圈定一些可采用的新技术。不要忘了，根据 ThoughtWorks 技术雷达来寻找合适的技术，会节省一些时间——毕竟已经有一些公司开始采用了。

可是不论怎样，别人说的东西，我们还是不信的。技术相关的东西，还是应该自己尝试一下，才能知道其中的好坏。所以，当我做了一系列的尝试之后，我发现对于自己而言，还是存在一些模式可以复用的，即如何做好技术调研。

## 调研示例：我的故事

最近的故事，我从我写那篇《无代码编程》的文章开始说起，那真的是一篇 TL;DR（太长不看）的文章，又长又是各种名词。可对于我来说，**整理资料最好的方式就是写一篇相关的文章** 。当自己能以自己的思路来描述相关概念的时间，才说明自己对相关的领域有一定的深入了解。**写作驱动学习**，是我的几大法宝之一。至于对于你而言，你是否需要写一篇文章才能理清自己的思路，那可就是因人而异。大抵是我的记忆力有限，所以我总会想把一些东西记下来，在我需要的时候，便随时可用——抛出一篇文章。

扯远了~。

在我开始调研的时候，我接收到的是一个单词『low-code programming』。于是，我打开了 Google，以了解一下相关的中文概念，发现没有（PS：笑，这真的是一个非常适合写的话题）。好吧，那我只能搜索一下英语相关的资料，自然而然的搜索到了大量的资料，可是呢，它们都是各种 Low-code development platform 相关的广告——我的意思是，绑定产品的概念介绍。然后我就开始了我的调研之旅：

 1. 收集相关的无代码开发平台，对于相关概念的介绍 。
 2. 了解无代码编程所需要的技术相关的信息。
 3. 整理无代码编程相关的优缺点。
 4. 尝试使用一些无代码开发平台。
 5. 结合自己的经验，设计一个无代码编程的原型。
 6. 撰写一篇相关的文章。

这么一些步骤下来，好吧，我发现这是我关于技术调研的相关**模式**。既然对于我来说，这是一个非常不错的套路，那么就顺写出一篇文章来吧。

## 如何做技术调研

太长不写。

### 0. 明确需求

多数时候，我们的需求都很明确。

但是，如果这是一个领导需求，那么：加油，少年。要么，你和你的领导进行 1：1 的谈话。要么你去猜领导的需求。

因为，沟通是一门艺术。**想的和说的，往往可能是不同的事**。

要么研究 React Native，可能是因为要采用跨平台方案，而不一定真的是要 React Native。毕竟，Flutter 可能会更满足你们的需求。

### 1. 诊断与信息收集

注意事项：

 - 从概念入手——Copy/Paste from Google/StackOverflow/Quora/Blogposts。
 - 优先关注于缺点，再关注于优点。
 - 只凭一篇文章是不够的——『一千个人眼中，就有一千个“哈利波特”』。

### 2. 整理相关信息

从写作的模式来看，要整理技术栈相关的内容，也存在一定的模式。这时我们关注于：

 - Why？
 - What？
 - How？
 - 优缺点？
 - 场景？
 - 问题？

有了这些套路，我们就能回答相关的问题了，最后再：**尝试用通俗易懂的语言，来向人们介绍相关的概念**。

### 3. 试用技术

倒是没啥说的：

 - 从官方示例代码开始
 - 结合真实业务场景编写 Hello, World

过程中，要注意一点：

 - 只编写通用模式相关的代码，**不要编写大量业务代码**。

### 4. 进行思考与回顾

我们在第 2 步中得到的结论，有可能是错的。所以，我们不得不重新理清相关的概念。

### 5. 构建 MVP

这是一个可选的步骤。只是作为一个程序员，我们还是喜欢造轮子的。

毕竟，如果只是写简单的 Hello, World，无助于我们理解相关的原理。

### 999. 做一次分享

嗯，好东西不要一个人憋着：

 - 写文章是一种分享；
 - 做 Session 分享是一种分享；

## 技术调研要做些什么？

### 一句话概括

结局，就是你能用一句话介绍出相关的技术和概念。

随后，再整理出电梯演进相关的方案，诸如于我在《架构拾集》中采用的：

| 关键因素 | 描述 |
| --- | --- |
| 对于 | |
| 我们的 | |
| 是一个 | |
| 它可以 |  |
| 但他不同于 | |
| 它的优势是 | |

### 优缺点分析

不管怎样，上 SWOT 吧——我觉得它可能是可行的。

### 适用场景

> 没有银弹。

不适合你们业务的技术，可能适合于别的场景。

反之，适合你们业务的技术，可能不适用于别的场景。

### 比较，比较，比较

当我们看到一个新的技术，我们总会和旧的技术栈进行比较。相似的，别人也会问你相关的问题。诸如于：

 - 无代码编程和 Dreamweaver 有什么区别？
 - Serverless 和微服务什么区别？
 - 如何在前端中使用微服务的概念？
 - Java 和 JavaScript 是什么关系？

### MVP

**没有代码，你就是在耍流氓。**

## 结论

**有钱捧个钱场，没钱转个分享。**

### 将 ________ 放入你最喜欢的电影场景中

想象一下：您邀请您的朋友来参加电影之夜。 最新的大片已经上映，所以你准备好了一切：披萨、爆米花、可乐。 你拉起电视/投影仪。 屏幕上的第一件事？ **你**！ 在电影播放之前，您所有的朋友都会看到一幅令人难以置信的艺术作品，将*您*描绘成主角。 每个人都会记住这个。

![](https://hackmd.io/_uploads/rJ1EHa4qi.png)

欢迎来到 AI 生成艺术的世界，通过一个名为“Stable Diffusion”的开源软件。 您之前可能听说过 Dall-e 或 MidJourney。 这些应用程序可让您从文本生成图像。 Stable Diffusion 是一个类似的项目，但它是免费和开源的——任何人都可以在自己的计算机上运行它！

像 Stable Diffusion 这样的开源模型是一个绝对的游戏规则改变者——你可以使用技术来微调它们并将它们与其他技术结合起来，以创建对你作为互联网上*任何*角色的极其准确的描述。

有没有想过在 2000 年的经典电影《美国惊魂记》中扮演帕特里克·贝特曼会是什么样子？ 蝙蝠侠？ 莱戈拉斯？ 毛茸茸？ 您可以通过 Stable Diffusion 实现它。

**这是计划**：

1. 我们将通过制作一堆非常酷的头像来学习所有关于提示的知识以及这项技术的工作原理
2. 接下来我们将深入研究这个叫做 Dreambooth 的东西 - 一种特殊的技术，让你**微调**特定主题（你！）的稳定扩散通过**教**你的样子
3. 然后我们将构建一个使用该模型的应用程序，这样您的朋友就可以使用它把您带到任何地方！

### 我们在建造什么？

这是我们将要做的事情的快速概述！

[https://vimeo.com/786750755](https://vimeo.com/786750755)

我们的应用程序背后的魔力在于为您定制它。 我们将只用您的笔记本电脑（或手机）为您拍摄完美的照片，并训练一个能够生成具有特定主题的疯狂 AI 头像的模型。 这一切只需提示 + 单击按钮即可。
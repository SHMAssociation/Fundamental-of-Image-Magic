---
description: 要想成功的释放任何法术，都需要性能足够优良的魔导器。钞能力是解决魔导器问题的最简单方法，否则需要较高的施法智慧。本书不对魔导器问题进行讨论。
---

# 第一章 像素魔法的要素

构建像素魔法通常会使用如下几大要素：

1. 正面咒语 <mark style="background-color:blue;">Prompt</mark>。控制魔法在哪些维度发挥作用。
2. 反面咒语 <mark style="background-color:blue;">Undesired Content</mark>。控制魔法，避免产生哪些效果。
3. 魔法规模 <mark style="background-color:blue;">Resolution</mark>。控制施法结果的尺寸。即使其他要素完全相同，但是魔法规模不同，施法结果是完全不同的，而非缩放和裁切的关系。在NovelAI中，首选512\*768规模的魔法。
4. 魔法基础模型 <mark style="background-color:blue;">model</mark>。基础模型决定了哪些咒语是有效的，产生的效果是如何的。在NovelAI中，目前基础模型有Curated，Full和Beta。
5. 魔法增补模型 <mark style="background-color:blue;">Hypernetwork</mark>。魔导士可以根据自己的需求，制作一个包含专有咒语的模型，作为基础模型的补充，和基础模型结合使用，从而获得个性化的魔法效果。
6. 魔力流转标尺 <mark style="background-color:blue;">Scale</mark>。可以控制施法结果的风格。
7. 魔力流转周数 <mark style="background-color:blue;">Step</mark>。施法结果是历经多个魔力流转周期后，才释放出来的。流转周期不同，施法结果亦不相同。
8. 施法种子 <mark style="background-color:blue;">Seed</mark>。如果不指定施法种子，每次施法时都会随机得到一个施法种子，从而产生不同的施法效果。
9. 魔导石 <mark style="background-color:blue;">Sampler</mark>。魔导石有不同的微调版本，主流的有K\_Eular\_a,K\_Eular,Eular\_a,Eular,DDIM等。

在性能足够的前提下，如果使用的要素完全相同且操作正确，使用任何公司制造的魔导器都能得到完全相同的施法结果，只有施法时间会存在差异。
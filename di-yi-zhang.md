# 第一章

构建像素魔法通常会使用如下几大要素：

1. 正面咒语。控制魔法在哪些维度发挥作用。
2. 反面咒语 <mark style="background-color:blue;">Undesired Content</mark>。控制控制魔法，避免发生哪些作用。
3. 魔法规模 <mark style="background-color:blue;">Resolution</mark>。控制施法结果的尺寸。即使其他要素完全相同，但是魔法规模不同，施法结果是完全不同的，而非缩放和裁切的关系。在NovelAI中，首选512\*768规模的魔法。
4. 魔法基础模型。基础模型决定了哪些咒语是有效的，产生的效果是如何的。在NovelAI中，目前基础模型有Curated，Full和Beta。
5. 魔法增补模型。魔导士可以根据自己的需求，制作一个包含专有咒语的模型，作为基础模型的补充，和基础模型结合使用，从而获得个性化的魔法效果。
6. 魔力流转标尺 <mark style="background-color:blue;">Scale</mark>。可以控制施法结果的风格。
7. 魔力流转周数 <mark style="background-color:blue;">Step</mark>。施法结果是历经多个魔力流转周期后，才释放出来的。流转周期不同，施法结果亦不相同。
8. 施法种子 <mark style="background-color:blue;">Seed</mark>。如果不指定施法种子，每次施法时都会随机得到一个施法种子，从而产生不同的施法效果。
9. 魔导石。魔导石有不同的微调版本



在魔导器性能足够的前提下，如果使用的以上要素完全相同，任何公司制造的魔导器都能得到完全相同的施法结果。

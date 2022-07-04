---
title: JPEG
slug: Glossary/jpeg
tags:
  - JPEG
translation_of: Glossary/jpeg
---
**JPEG**（联合图像专家小组） 是一个广泛用于数字图像有损压缩的方法。

**JPEG**（Joint Photographic Experts Group）是 JPEG 标准的产物，该标准由国际标准化组织（ISO）制订，是面向连续色调静止图像的一种压缩标准。JPEG 格式是最常用的[图像文件格式](https://baike.baidu.com/item/%E5%9B%BE%E5%83%8F%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F/10728158)，后缀名为.jpg 或.jpeg

## 简介

**JPEG**（Joint Photographic Experts Group）即联合图像专家组，是用于连续色调静态[图像压缩](https://baike.baidu.com/item/%E5%9B%BE%E5%83%8F%E5%8E%8B%E7%BC%A9/8325585)的一种标准，文件后缀名为，jpg 或，jpeg，是最常用的图像文件格式。其主要是采用[预测编码](https://baike.baidu.com/item/%E9%A2%84%E6%B5%8B%E7%BC%96%E7%A0%81/5907587)（DPCM）、[离散余弦变换](https://baike.baidu.com/item/%E7%A6%BB%E6%95%A3%E4%BD%99%E5%BC%A6%E5%8F%98%E6%8D%A2/7118270)（DCT）以及[熵编码](https://baike.baidu.com/item/%E7%86%B5%E7%BC%96%E7%A0%81/3303605)的联合编码方式，以去除冗余的图像和彩色数据，属于[有损压缩](https://baike.baidu.com/item/%E6%9C%89%E6%8D%9F%E5%8E%8B%E7%BC%A9/2311513)格式，它能够将图像压缩在很小的储存空间，一定程度上会造成[图像数据](https://baike.baidu.com/item/%E5%9B%BE%E5%83%8F%E6%95%B0%E6%8D%AE/5199370)的损伤。尤其是使用过高的压缩比例，将使最终[解压缩](https://baike.baidu.com/item/%E8%A7%A3%E5%8E%8B%E7%BC%A9/2471723)后恢复的图像质量降低，如果追求高品质图像，则不宜采用过高的压缩比例。<sup></sup>

然而，JPEG 压缩技术十分先进，它可以用有损压缩方式去除冗余的图像数据，换句话说，就是可以用较少的磁盘空间得到较好的图像品质。而且 JPEG 是一种很灵活的格式，具有调节[图像质量](https://baike.baidu.com/item/%E5%9B%BE%E5%83%8F%E8%B4%A8%E9%87%8F/5133364)的功能，它允许用不同的压缩比例对文件进行压缩，支持多种压缩级别，压缩比率通常在 10；1 到 40；1，压缩比越大，图像品质就越低；相反地，压缩比越小，图像品质就越高。同一幅图像，用 JPEG 格式存储的文件是其他类型文件的 1/10\~1/20，通常只有几十 KB，质量损失较小，基本无法看出。JPEG 格式压缩的主要是高频信息，对色彩的信息保留较好，适合应用于互联网；它可减少图像的传输时间，支持 24 位真彩色；也普遍应用于需要连续色调的图像中。

JPEG 格式可分为标准 JPEG、渐进式 JPEG 及 JPEG2000 三种格式。

1\. 标准 JPEG 格式；此类型在网页下载时只能由上而下依序显示图像，直到图像资料全部下载完毕，才能看到图像全貌。<sup></sup>

2\. 渐进式 JPEG；此类型在网页下载时，先呈现出图像的粗略外观后，再慢慢地呈现出完整的内容，而且存成渐进式 JPG 格式的文档比存成标准 JPG 格式的文档要来得小，所以如果要在网页上使用图像，可以多用这种格式。<sup></sup>

3\. JPEG2000；它是新一代的影像压缩法，压缩品质更高，并可改善在无线传输时，常因信号不稳造成马赛克现象及位置错乱的情况，改善传输的品质。

## 性能

JPEG 的性能，用质量与[比特率](https://baike.baidu.com/item/%E6%AF%94%E7%89%B9%E7%8E%87/1022775)之比来衡量，是相当优越的。

**JPEG 的优点是：**

- 它支持极高的压缩率，因此 JPEG 图像的下载速度大大加快。
- 它能够轻松地处理 16.8M 颜色，可以很好地再现全彩色的图像。
- 在对图像的压缩处理过程中，该图像格式可以允许自由地在最小文件尺寸（最低图像质量）和最大文件尺寸（最高图像质量）之间选择。
- 该格式的文件尺寸相对较小，下载速度快，有利于在带宽并不“富裕”的情况下传输。

**JPEG 的缺点是：**

- 并非所有的浏览器都支持将各种 JPEG 图像插入网页。
- 压缩时，可能使图像的质量受到损失，因此不适宜用该格式来显示高清晰度的图像。

JPEG 的复杂度之低和使用时间之长，给人以深刻的印象。以下是对于 8 位/像素的中等复杂画面的图像，JPEG 所给出的几个等级作为衡量压缩编码效果的准则：

- 0.25 位/像素\~0.5 位/像素；中\~好，足以满足一些应用。<sup></sup>
- 0.5 位/像素\~0.75 位/像素；好\~很好，足以满足许多应用。
- 0.75 位/像素\~1.5 位/像素；优秀，足以满足大多数应用。<sup></sup>
- 1.5 位/像素\~2.0 位/像素；难于与原图像区别，足以满足绝大多数应用。<sup></sup>
- \>2.0 位/像素；近乎完美，满足几乎全部的应用。

其中位/像素（bit/pixel）定义为压缩图像（包括色度分量）的总位数除以亮度分量的样本数。

## 了解更多

### 常识

- 在维基百科上的 {{Interwiki("wikipedia", "JPEG")}}
- 在百度百科上的 [jpeg](https://baike.baidu.com/item/JPEG%E6%A0%BC%E5%BC%8F/3462770)
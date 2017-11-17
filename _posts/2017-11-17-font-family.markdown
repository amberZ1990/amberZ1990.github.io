---
layout:     post
title:      "Font Family"
subtitle:   'web font'
date:       2017-11-17
author:     "Amber"
header-img: "img/post-bg-2017-2.jpg"
tags:
    - 前端开发
---
>Font Family
## 关于字体


* 使用哪种web字体这取决于: <br> 1. 你的产品要在哪个系统上运行<br> 2. 你的产品是纯英文还是中文英文甚至还有其他国家语言为什么这么
说？

* 字体一直都是让设计师和工程师头疼的问题。如果参与过产品的设计和开发，会发现经常有以下这种情况出现：<br> 1. 对比视觉稿和实现出来的网页，其他地方都很完美，就字体不给力。
<br> 2. 在 Mac 上很好看，在 Windows 上丑的要死；iPhone 和 Android 又不同……为什么？


* 真正的幕后黑手是系统。浏览器使用哪种字体取决于：<br>
1. 你的系统安装了哪些字体（我原来以为浏览器自己也会带字体，这是错误的，感谢知友的提醒）<br> 
2. 工程师有没有让用户去下载其他字体看看知乎专栏和苹果官网在网页中使用了哪些字体：<br> 
知乎专栏：'Open Sans','Helvetica Neue',Arial,'Hiragino Sans GB','Microsoft YaHei','WenQuanYi Micro Hei',sans-serif<br> 
苹果官网："Lucida Grande", "Lucida Sans Unicode", Helvetica, Arial, Verdana, sans-serif<br> 
有些设计师会问，怎么会有这么多字体？<br> 
打个比喻：可以想一下去超市买脉动的情景：我最希望买到的是菠萝味，其次是蓝莓、橘子、荔枝……这些都没有就矿泉水;浏览器会这样去选择：知乎专栏为例，从前往后，'Open Sans'，'Helvetica Neue'……<br> 
有人会问，为什么不自己带脉动？沉啊。对于网站来说，下载个字体还是要费很大劲的。英文字体 26个大写+26个小写+标点符号不是
很多，但中文汉字的数量…… 所以很少有网站会去让用户去下载中文字体的。<br> 


* 最优解：你可以使用多种字体，看一下在每种字体上的效果。把效果最好的字体放在最前面，在后面多加几个后备军。例如Open Sans 的中文字体在 Mac 上效果不错。微软雅黑的中文字体在 Windows 上效果不错<br>

<a style="color:#999;font-size:12px;">
        来源：知乎https://www.zhihu.com/question/19680724/answer/18246488</a>        



| 站点| 字体列表
| ------------- |:-------------
| 百度pc|arial,"Hiragino Sans GB","Microsoft Yahei","微软雅黑","宋体",Tahoma,Arial,Helvetica,STHeiti
| 百度手机|Arial,Helvetica,sans-serif
| 天猫手机|Helvetica,sans-serif
| 天猫pc|tahoma, arial, 宋体      
|京东pc|Microsoft YaHei,tahoma,arial,Hiragino Sans GB,\5b8b\4f53,sans-serif
|京东手机|Microsoft YaHei",Arial,Helvetica,sans-serif
|蘑菇街pc|tahoma,arial,sans-serif
|蘑菇街手机|Arial
|微信|-apple-system-font,Helvetica Neue,PingFang SC,Hiragino Sans GB,Microsoft YaHei,sans-serif
|知乎|-apple-system,BlinkMacSystemFont,Helvetica Neue,PingFang SC,Microsoft YaHei,Source Han Sans SC,Noto Sans CJK SC,WenQuanYi Micro Hei,sans-serif
|Github|-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol" 
|VUE|"Source Sans Pro", "Helvetica Neue", Arial, sans-serif
|WEEX|"Source Sans Pro", "Helvetica Neue", Arial, sans-serif
|codePen 英文|"Lato", "Lucida Grande", "Lucida Sans Unicode", Tahoma, Sans-Serif
|apple China|"SF Pro Text","SF Pro Icons","Helvetica Neue","Helvetica","Arial",sans-serif
|国内某产品pc|"Lantinghei SC", "Open Sans", Arial, "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", "STHeiti", "WenQuanYi Micro Hei", SimSun, sans-serif
|方糖气球(easy)|"Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","\5FAE\8F6F\96C5\9ED1",Arial,sans-serif
|某知乎er|"PingFang SC", "Helvetica Neue", "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", Helvetica, Arial, Verdana, sans-serif;mac 用户优先选择苹方，win 用户优先选微软雅黑。
|小桔科技某H5|-apple-system,BlinkMacSystemFont,'Helvetica Neue',Helvetica,'Nimbus Sans L',Arial,'Liberation Sans','Hiragino Sans GB','Source Han Sans CN Normal','Microsoft YaHei','微软雅黑','Wenquanyi Micro Hei','WenQuanYi Zen Hei','ST Heiti',SimHei,'WenQuanYi Zen Hei Sharp',sans-serif
|大自然保护协会 M端(pc端使用inherit)|"din","Hiragino Sans GB","Helvetica","Microsoft YaHei","微软雅黑","宋体"
|大神字体|-apple-system,"Helvetica Neue",Arial,"PingFang SC","Hiragino Sans GB",STHeiti,"Microsoft YaHei","Microsoft JhengHei","Source Han Sans SC","Noto Sans CJK SC","Source Han Sans CN","Noto Sans SC","Source Han Sans TC","Noto Sans CJK TC","WenQuanYi Micro Hei",SimSun,sans-serif

整理 <sub>by</sub> 赵雪峰
---
layout: post
title: Netbook上的Jolicloud
categories:
- 技术
tags: []
status: publish
info: 杭州
type: post
published: true
meta: {}
---

ChromeOS的发布也就是在这几天的事情，当然，如同我们知道的，ChromeOS并非是纯粹的免费系统，它最终将以预装的形式随厂商的网本发布：像可能吧的评论文章一样，我对它的短期前景，特别是国内前景并不看好，原因很简单：所谓最大噱头的网络服务应用，web2.0的诸多网站，对于境内用户来说，根本就无法正常访问，这不是白搭么？作为天朝子民，越是优秀的网络服务，我们就越有可能无法访问，这几乎已经成为至理。

至于其余品牌知名度，商业推广模式等等就先不用说了。

更何况，除非愿意在虚拟机上编译源代码尝鲜，否则ChromeOS至少目前好像并不是那么方便应用的。

但是无意间看到的另外一个网本OS的项目， [Jolicloud](http://www.jolicloud.com) ，也算是挺有意思的一个发现了。

脱胎于Ubuntu的jolicloud，算是一个针对netbook的定制版。

其中很多想法算是得自于ChromeOS的启发，而且阐发的很好：    首先，一切服务都能够'web'化的思维。

在这里也许区别就在于这些服务的独立化并非依靠google chrome，而是靠firefox的prism扩展的实现——当然，这里的firefox也是通过专门jolicloud扩展优化过的——twitter，facebook，google talk，gmail， google reader，等等都是已经作为定制模块和其他程序一起放在程序中心备选安装，当然作为中国用户，对其中很多都只有望洋兴叹罢了；   其次，简化用户接口，针对网本小屏幕，大图标居中排列的UI设计很是醒目 :   程序打开时，一般就是直接自动最大化占据全屏，仅仅只有顶端标题栏和系统托盘区，任务区低调存在，感觉大气不少；和dropbox服务漂亮的整合，如果是小硬盘的网本，更是意义非凡（希望不要被GFW盯上）。

尤其值得一提的是jolicloud的用户中心相当让人期待。

这里可以修改用户配置（事实上也就是用户在jolicloud服务器端配置）；可以安装卸载官方整理的软件和服务，如前文提到的很多服务，都是整理后分类放在这里，还有打分机制；可以自动寻找和管理软件以及系统的更新升级；……还可以follow其他的jolicloud用户，目前还只是能够看到一些软件系统更新信息，但是继续发展下去，如果能和一些社会化媒体深度整合，那么jolicloud可以轻易发展成一个社区化的网本OS。

安装过程并不复杂，我的eeepc是堂堂正正的写在兼容列表里的设备，我只需要下载600M的iso以及一个usb安装盘制作软件，简单双击，就可以制造一个用于boot和安装的u盘了。

然后从usb启动，安装，非常简单。

只是后续过程里，不停的系统更新提醒纷至沓来，花了我小半天才终于up to date了……非常满足。

不得不说，ubuntu本身就是个很方便的系统，在有网络的状态下，软件的安装是相当的麻利。

而且可能也是jolicloud做过一些优化，以前比较麻烦的中文化工作，包括输入法，都是在选择并且安装中文支持后自动到位，相当省心。

当然，毕竟不算是彻底的重新设计的发行版，有些地方也会流露出包装不充分的样子来，而且如果真是一个着眼于web2.0或者说社会化媒体的操作系统，在消息推送整合上本来应该有更大的增强——不妨参见近期Moto和Nokia的几款新手机的设计。

当然，这样的要求对于jolicloud来说可能有点为难了。

依然要提到的是，作为国内用户，这样一个操作系统，也只能说是作为netbook上的家庭第二系统使用，因为那些firefox，chrome永远无法正常访问的网银系统以及形形色色的ie only的网站。

而这些'不和谐'的东西注定要在相当长的一段时间里在中国长期存在。

而且，作为国内用户，你也依然只能对着那些优秀的网络应用喟叹:twitter, facebook, friendfeed, picasa 等等，而且越来越多的其他服务也正在得到墙的关注。

就在昨天，很多人就诧异的发现，手机翻墙的利器，国际版的opera mini，对于中国ip再也无法使用，这条小路都被堵死，让人心凉。

也许终有一天，我们会发现可以被访问的东西要少于不能被访问的，一张真正的'史上最大的'局域网就要在中国建成，而如同马伯庸笔下的'寂静之城'一样，我们能说的词要少于被过滤的词。

到那时，我们要学会从满篇的星号中揣摩作者的意思了。

PS.村上的新书，'1Q84'的简体中文版，不知道什么时候才会出版呢？等待中...    


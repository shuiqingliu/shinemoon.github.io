---
layout: post
title: 'Firefox下载网络视频的快捷方法'
categories:
- 技术
tags: [firefox]
status: publish
info: 上海
type: post
published: true
meta: {}
---

用Firefox的人大多恐怕知道Downloadhelper这个插件。它能够自动嗅探页面里的流媒体，特别是目前流行的FLV格式的视频地址（比如土豆网、酷6等等，其实都是使用这种格式）。我最初并不喜欢它，主要是嫌它的图标太难看了，影响我的界面美观——可是一通搜索下来，竟然发现，这样一个普遍的、有意义的需求，除了它，居然硬找不到一个更好的了。大部分的类似插件都是支持国外几个网站，比如Youtube就满足了，这在国内完全不实用，不得已，只好依然装好了它。用在土豆上还凑合，虽然界面谈不上友好（文件名经常让我很郁闷，搞不清楚谁是谁）；可是当我试图去优酷时，郁闷的发现，优酷居然是把好好的flv切段，然后封起来，所以downloadhelper没法直接看到后面的部分，这下彻底从不好用变成几乎没法用了。

我想起了http://www.flvcd.com（其实就是很多人熟悉的kisstudou），它的兼容性是没得说了，可是难道我只好老老实实的在网页上敲地址来解析视频么？这实在不爽。

我又想起了我很喜欢的redirector ：我直接把任何视频的地址直接转成flvcd的搜索结果地址不就ok了。于是解决方案出来了。

很简单，flvcd的搜索的输入就是视频页面的地址，那么任何网站只要做类似的替换就可以了，比如：

以此类推，以后只要点击任何这些网站的地址，都会自动转到flvcd的解析结果页面——怎么下载，看你喜欢了。我是使用flashget1.96的，因为至少对土豆来说，需要在选项中的协议栏里，把’发送引用页‘取消掉，否则无法下载，而flashget2居然找不到设置这个地方，郁卒。

那么，新的问题出现了，我不想写太复杂的表达式来过滤，但是这样的话所有的tudou或者youku的地址都转到flvcd了，怎么搜索和查看视频呢——这个其实最好办了，任何时候找视频，直接用百度视频好了，搜出的内容直接点击，得到直接地址，然后下载，实在方便很多。

另外，如果还懒一点，顺便再把百度视频加到搜索栏里好了，Add to search bar这个时候就派上用场了......
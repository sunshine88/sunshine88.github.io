---
layout: post
title:  "用jPages"
desc: "Jekyll自带的分页功能总不是那么全，为了达到更好的分页效果，在不同类别的文章下进行分页，就要用别的方法来实现了。"
keywords: "Jekyll,pagination,jPages,javascript"
date:   2016-06-04
categories: [HTML]
tags: [pagination,jekyll]
icon: icon-html
---


Jekyll自带的分页功能总不是那么全，在官方文档中有讲到Jekyll自带分页的使用方法，为了达到更好的分页效果，比如在不同类别的文章下进行分页，就要用别的方法来实现了。

首先，在网上我也找到了很多Jekyll的第三方插件，功能很强大，不过github不允许使用，无奈之下只好另寻他法。因为平时做网站开发想到的都是后端分页的方法，那么在github这个不用考虑性能的网站上，我们为什么不能尝试使用前端分页的方法呢？而且我们的文章也不是非常多，一次得到所有数据再分页未尝不可。就这样，我在网上找到了一些基于jQuery的前端分页插件，使用感觉最好的就是jPages了。

jPages的文档很详细，每种分页的方法从html、JavaScript到CSS都有源代码，并有展示，这里我讲一下我是怎么用到jekyll中，我使用的是items per page这个example：

   <object type="application/x-shockwave-flash" class="player" data="http://static.hdslb.com/play.swf" width="950" height="482" id="player_placeholder" style="visibility: visible;"><param name="bgcolor" value="#ffffff"><param name="allowfullscreeninteractive" value="true"><param name="allowfullscreen" value="true"><param name="quality" value="high"><param name="allowscriptaccess" value="always"><param name="wmode" value="direct"><param name="flashvars" value="cid=8263339&amp;aid=5086838&amp;pre_ad=0"></object>
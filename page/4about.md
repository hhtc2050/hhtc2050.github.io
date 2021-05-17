---
layout: page
title: About
permalink: /about/
icon: heart
type: page
---

* content
{:toc}

## 关于袭胸资管

<iframe src="https://githubbadge.appspot.com/gaohaoyang?s=1" style="border: 0;height: 142px;width: 200px;overflow: hidden;" frameBorder="0"></iframe>

1、“袭胸”一词的渊源是什么？
我们认为：炒期货就是袭胸，只找大波偷袭，得手了多摸会儿，失手了赶紧跑路。

2、贵公司核心竞争力是什么？
袭胸九式。

3、袭胸九式开源代码
DRAWCOLORKLINE(ISUP,COLORRED,1);
DRAWCOLORKLINE(ISDOWN,COLORCYAN,0);
DRAWCOLORKLINE(ISEQUAL,COLORWHITE,1);
MA20:MA(C,20),COLORGRAY;
TOP:MA20+2*STD(CLOSE,20),COLORGRAY;
BOT:MA20-2*STD(CLOSE,20),COLORGRAY;
DRAWICON((H-(MAX(O,C))>0.382*(H-L)) AND H>TOP,H,'5');
DRAWICON(((MIN(O,C)-L)>0.382*(H-L)) AND L<BOT,L,'4');
OPID:OPI;
MA20:=MA(V,20);
TOP:=MA20+2*STD(V,20);
STICKLINE(V<TOP,0,V,COLORGRAY,0);
STICKLINE(V>TOP,0,V,COLORRED,0);
DRAWICON(V>3*MA20,V,'6');

## 业务合作
电话13451938885，可加微信

{% include comments.html %}

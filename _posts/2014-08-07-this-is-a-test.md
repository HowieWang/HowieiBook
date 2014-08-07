---
layout: post
title: "Override Author Byline Test Post"
description: "An article to test overriding the default site author."
category: articles
tags: [sample-post, readability, test]
author:
  name: Howie
  avatar: bio-photo-alt.jpg
comments: true
share: true
---

我就是个测试文档，顺便看看中文显示对不对。

{% highlight yaml %}
author:
  name: Howie
  avatar: billy-photo.jpg    #place in /images
  twitter: billyrick         #marked as a creator for Twitter Card links
{% endhighlight %}

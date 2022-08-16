---
title: "Datasette Sqlite"
date: 2022-08-16T06:39:35+08:00
draft: false
---

有一两年了，在油管上看到一个pycon的演讲，主题是 https://datasette.io ，作者是Simon Willison。datasette是一个Python的包，也是一个数据展示的生态。可以通过`pip install datasette` 来安装。

这个工具的的核心是在浏览器里展示`sqlite`数据库文件的内容。

为什么要用sqlite呢？sqlite作为一个文件数据库，在互联网上的应用处理并发是不合适的，但是，作为一个只读的内容承载，是非常好的。有两篇参考文档可以看：

https://simonwillison.net/2021/Jul/28/baked-data/

https://mozilla.github.io/meao/2018/03/28/bedrock-the-sqlitening/

最近，在阮一峰的网摘上，也收录里一篇SQLite背后的故事，很有趣。

https://liyafu.com/2022-07-31-sqlite-untold-story/

文摘链接在这里：

https://www.ruanyifeng.com/blog/2022/08/weekly-issue-217.html

可以好好研究一下这两个工具，挖掘一下。
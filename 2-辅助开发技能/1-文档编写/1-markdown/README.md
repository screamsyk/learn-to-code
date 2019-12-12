# Markdown

参考资料：

> [Markdown 作者官网](https://daringfireball.net/projects/markdown/)

> [Markdown 是什么？](https://mp.weixin.qq.com/s/q6C-XOW9peMPTjFRVHJw4A)

> [一篇最详细的 Markdown 教程](https://mp.weixin.qq.com/s/BfpGnJtEVPGJIOXo0PV8Hw)

> [Markdown 语法图文详解](https://mp.weixin.qq.com/s/Dx6cz_37hnCcqBKKYXwxBw)

> [为什么不应该使用Markdown来写文档](https://mp.weixin.qq.com/s/IwnLE-rX2wlfCAW8tDSRFg)

> [如何在公众号中写数学公式](https://mp.weixin.qq.com/s/J2Z6SlMYLjeIqp635DqOXQ)

## 一、概念

Markdown 是 2004 年由 Aaron Swartz 和 John Gruber 共同设计的，有两层含义：

```
1. 一种轻量级标记语言，它允许用纯文本格式（易读、易写）来编写文档，通过简易的标记，使文本具有一定的格式。

2. 一种将纯文本转换为 HTML 的工具。
```

现在提到的 Markdown，主要是指轻量级标记语言，因为将 Markdown 文本（后缀为 `.md` 或 `.markdown`）转换为 HTML 或者其他形式的工具多种多样。

## 二、发展

最初，Markdown 由 John Gruber 提出后，附带提供了一个将 Markdown 文本转换为 HTML 的解析工具，也叫 Markdown。

随着 Markdown 的流行，许多网站（如 GitHub）和编辑器（如 VSCode、Typora）开始支持 Markdown，并有了它们自己的 Markdown 实现和解析工具。

这些多样的实现，使 Markdown 有很多衍生版本，扩展了 Markdown 的功能（如表格、脚注、内嵌 HTML 、数学公式等）。

但由于没有明确的规范，导致各个 Markdown 实现上，虽然基本语法都兼容，但一些写法上却大不相同，比如：

```
标题的标记和文本之间，有的实现要求留空格，有的又不需要留空格：

# 标题1（留空格）

#标题1（不留空格）
```

同时一些支持的功能上，也不相同，比如 Typora 编辑器支持数学公式，但很多其他的实现却不支持。

所以使用 Markdown 时，要注意我们是基于什么实现的，采用的什么解析工具。

## 三、语法

---
title: "如何编写 README.md / Markdown 文件？"
date: 2022-07-21T04:15:49+08:00
tags: ["翻译", "Markdown"]
categories: "入门"
---

> 本文翻译自 [Medium](https://medium.com/@saumya.ranjan/how-to-write-a-readme-md-file-markdown-file-20cb7cbcd6f)

在这篇文章中，你将了解到什么是 Markdown 文件，以及如何编写 Markdown 文件。你可以在很多远程仓库中找到这种文件。

## 什么是 README.md 文件？

README.md 是一个简单的纯文本文件，它包含了项目的基本信息和一些指南，常被作为安装指南或项目内的基本文档。许多主流的代码托管平台，像 GitHub、GitLab 和 Bitbucket，都使用 README.md 作为概述文件。

## 什么是 Markdown？

![Markdown Logo](/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E4%BB%80%E4%B9%88%E6%98%AF%20Markdown-01.png#center)

Markdown 是一种轻量级标记语言，它能够将纯文本格式化为各种样式，并很快就被一些博文网站用于内容写作。简单和易懂的特点使得 Markdown 很受欢迎，它将纯文本选择性地转换为 HTML 格式：从 Markdown 文件中获取所有文本，并通过 Markdown 应用程序或编译器转换为 HTML。

![Render Markdown File](/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E4%BB%80%E4%B9%88%E6%98%AF%20Markdown-02.png#center)

如果你刚开始接触 Markdown，那么这篇文章就是为你准备的。我会一步一步编写 README.md 文件，来让你慢慢熟悉 Markdown。

这里我用 Visual Studio Code 来编写 Markdown 文件，下面是在 Visual Studio Code 中创建 Markdown 文件的步骤。

第 1 步：打开 Visual Studio Code 并点击 `File > New File...` / `文件 > 新建文件...`

第 2 步：将文件命名为 `readme.md` 或 `readme.markdown` 并保存。

第 3 步：找到并点击 `Open Preview to the Side` / `打开侧边预览` 图标。

![VS Code Screenshort](/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E4%BB%80%E4%B9%88%E6%98%AF%20Markdown-03.png#center)

第 4 步：开始编写文件。

## 标题

标题都是以井号 `#` 开头的，不同数量的井号代表了不同的级别。

{{< figure src="/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E6%A0%87%E9%A2%98-01.jpg" align=center title="Markdown 的标题" >}}

你最多可以写到六级标题

## 普通文本

如果你只是想写点普通文本，直接输入就可以了，无需添加任何标记，它会被自动转换为正文。

{{< figure src="/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E6%99%AE%E9%80%9A%E6%96%87%E6%9C%AC-01.jpg" align=center title="你可以在 Markdown 文件中编写普通文本" >}}

## 超链接

你可以像下面那样在 Markdown 文件中添加超链接。

`[链接文字](目标地址)`

例如：`[Github](https://www.github.com)`

你也可以写上链接的标题（把鼠标移上去的时候会显示）。

`[链接文字](目标地址 "标题")`

例如：`[Github](https://www.github.com "Github 主页")`

![Hyperlink Example](/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E8%B6%85%E9%93%BE%E6%8E%A5-01.jpg#center)

> 注意：目标地址和标题之间要有个空格。

## 加粗和斜体

在文本的前后都加上一个下划线 `-` 就可以让文文字变成斜体；前后都加上两个星号 `**` 可以加粗文字了。

![Strong and Italic Text Example](/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E5%8A%A0%E7%B2%97%E5%92%8C%E6%96%9C%E4%BD%93-01.jpg#center)

## 删除线

如果你想划掉一些文字，只需要在两头加上两个波浪号 `~~` 就可以了。

![Strikethrough Example](/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E5%88%A0%E9%99%A4%E7%BA%BF-01.jpg#center)

## 图片

你可以像下面那样在 Markdown 文件中添加图片。

`![图片名称](图片地址)`

![Image Example](/%E5%A6%82%E4%BD%95%E7%BC%96%E5%86%99%20README.md%20Markdown%20%E6%96%87%E4%BB%B6/%E5%9B%BE%E7%89%87-01.jpg#center)

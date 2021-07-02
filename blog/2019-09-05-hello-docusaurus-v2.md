---
title: 欢迎来到 Docusaurus v2
author: Joel Marcey
author_title: Docusaurus 1 创建者之一
author_url: https://github.com/JoelMarcey
author_image_url: https://graph.facebook.com/611217057/picture/?height=200&width=200
tags: [hello, docusaurus-v2]
description: 这是我在 Docusaurus 2 上的首篇博文。
image: https://i.imgur.com/mErPwqL.png
hide_table_of_contents: false #是否隐藏右侧的目录。 默认情况下为 false。
---
欢迎来到此博客。 此博客使用 [**Docusaurus 2**](https://docusaurus.io/) 搭建。

<!--truncate-->

这是我在 Docusaurus 2 上的首篇博文。

下方是一系列内容。

export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>
    {children}
  </span>
);

<Highlight color="#25c2a0">Docusaurus green</Highlight> and <Highlight color="#1877F2">Facebook blue</Highlight> , <Highlight color="#010">黑色</Highlight>are my favorite colors.

I can write **Markdown** alongside my _JSX_!
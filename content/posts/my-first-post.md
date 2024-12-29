+++
date = '2024-12-29T01:29:36+08:00'
draft = true
title = 'My First Post'

+++

\## Introduction This is **bold** text, and this is _emphasized_ text. Visit the [Hugo](https://gohugo.io) website!

初始化站点

```
hugo new site qwqaq-blog

```

## 内容目录

/content/ 为内容存放目录，创建新的文章执行：

```
hugo new posts/hello-world.md
```

文章 hello-world.md 会使用 /archetypes/ 中的模板创建，完整路径：/content/posts/hello-world.md

## 头字段（FrontMatter）

应该叫做 FrontMatter，我也不知道中文叫什么，就叫头字段吧。就是生成的 markdown 文件最前面的那个家伙：

当你使用`hugo new posts/your_post.md`新建文章的 markdown 文件时，该文件已默认创建了包括标题、创建时间等信息。

这些元数据被称为`Front Matter` ，如果你需要了解 Hugo 预定义的 `Front Matter` 或更多关于 Front Matter 的内容，可以参考。 主题会提供默认的格式及内容，这些信息保存在 themes/yourtheme/archetypes/posts.md，

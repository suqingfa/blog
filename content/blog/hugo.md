+++
title = 'Hugo使用总结'
date = 2023-11-05T21:23:22+08:00
draft = true
+++

# 快速开始

https://gohugo.io/getting-started/quick-start/

```shell
hugo new site blog
cd blog
git init
git submodule add https://github.com/nanxiaobei/hugo-paper.git themes/hugo-paper
echo "theme = 'hugo-paper'" >> hugo.toml
hugo server
```

# 主题列表

https://themes.gohugo.io/

# 添加内容

````shell
hugo new content posts/my-first-post.md
````

```markdown
---
title: "My First Post"
date: 2022-11-20T09:03:20-08:00
draft: true
---

## Introduction

This is **bold** text, and this is *emphasized* text.

Visit the [Hugo](https://gohugo.io) website!
```

# 发布

```shell
hugo
```

# 配置
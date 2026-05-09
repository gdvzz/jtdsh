---
title: prompt
layout: default
# nav_order: 0
nav_exclude: true
---

# 提示词
`更新-260428` \| `发布-260428`

用于集成 Pagefind 到 jtd。

1、 用just-the-docs theme建的github pages 网站，只支持英文搜索，不支持中文搜索。怎么优化可支持中文搜索？

2、当前文件夹目录如下：

├── .github
│   ├── dependabot.yml
│   └── workflows
│       ├── ci.yml
│       └── pages.yml
├── .gitignore
├── LICENSE
├── README.md
├── docs
│   ├── Gemfile
│   ├── Gemfile.lock
│   ├── _config.yml
│   ├── index.md
│   └── prompt.md
└── index.md.bak

3、 _config.yml、ci.yml、pages.yml、dependabot.yml，内容如附件

4、中文搜索使用 pagefind

5、git push 推送到 github，git Action 编译可以通过。

6、如何使用 pagefind 做搜索，可以搜索中文、英文，或者中英文混合

- 每页顶部有个搜索
- 输入要搜索的内容，点击搜索按钮就可以搜索


```bash
~/gdvzz/jtdsh % tree -a -I '.git'
.
~/gdvzz/jtdsh % tree -a -I '.git'
.
├── .DS_Store
├── .github
│   ├── dependabot.yml
│   └── workflows
│       ├── ci.yml
│       └── pages.yml
├── .gitignore
├── LICENSE
├── README.md
├── docs
│   ├── Gemfile
│   ├── Gemfile.lock
│   ├── _config.yml
│   ├── index.md
│   └── prompt.md
└── index.md.bak
```


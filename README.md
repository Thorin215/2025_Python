# Python 2025

本仓库用来发布2025年春夏上机课程文档，你可以直接查看[在线文档]([2025_DD](https://blog.thorin215-wang.com/2025_Python/))，或将本仓库拉至本地部署。

本文档面向对象为 2025-2026 秋冬学期《Python程序设计》**沈钦仙老师**班和**孟炳泉老师**班。

> 非常欢迎同学向本仓库提交自己的笔记！

## 如何在本地构建？

本文档使用 [mkdocs](https://www.mkdocs.org/) 构建，并使用了 [material](https://squidfunk.github.io/mkdocs-material/) 第三方主题，你需要在本地依次序安装 [Python](https://python.org)、mkdocs、material 主题、heti 插件。

### Python 安装

官网[安装指导](https://wiki.python.org/moin/BeginnersGuide/Download)已经给出各系统安装方式，根据官网内容安装即可。

### mkdocs、material 主题、插件

均可以通过 [pip](https://pypi.org/project/pip/)（Python 的包管理器）进行安装。

```bash
$ pip install mkdocs
$ pip install mkdocs-material
$ pip install mkdocs-heti-plugin
```

具体地，你可以分别查看 [mkdocs 的安装指导](https://www.mkdocs.org/getting-started/#installation) 与 [material 的安装指导](https://squidfunk.github.io/mkdocs-material/getting-started/#installation)。

### 本地构建

你只需要将本仓库拉至本地，后使用 `mkdocs serve` 部署即可。

```bash
# 拉取仓库，两者皆可
$ git clone git@github.com:Thorin215/2025_Python.git
$ git clone https://github.com/Thorin215/2025_Python.git
# 构建
$ cd ./2025_DD
$ mkdocs serve
```

如果你使用本地部署查看文档，请在每次使用前查看并拉取远程仓库的 `main` 分支更新 `git pull`。

## 如何提建议

本人水平有限，文档难免有错误以及排布不合理之处。

如果你：

* 发现文档有知识性或实践性的错误
* 发现文本中的错别字/格式错误/图片缺失
* 对文档有建议

欢迎提交 Issue/PR 或通过邮箱与我沟通，我的邮箱为 zjuheadmaster@zju.edu.cn 。

非常期待得到你的反馈！

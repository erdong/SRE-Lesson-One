# 帮助文档

gitbook-notes-samples 是一个基于 GitBook 的学习笔记的模板 。

# 必备要求

使用该模板需要先安装 Git 、Nodejs 、GitBook 命令行。

安装 Git

```
yum install git
```

安装 Nodejs

```
$ wget -qO- https://raw.github.com/creationix/nvm/v0.33.11/install.sh | sh
$ nvm install stable
```

安装 GitBook 命令行工具

```
$ npm install gitbook-cli -g
```

# 插件说明

本仓库将插件也一起上传到了仓库中，在任何一台机器上安装好工具、配置好 Git 以后就可以直接工作了，而且生成的页面都是一样的。

* pageview-count : 统计页面浏览次数

* back-to-top-button : 添加一个返回页面顶部的按钮

# 使用说明

## 目录

请按照自己的实际情况修改 `README.md` 和 `SUMMARY.md` 两个文件中的目录，以及 `README.md` 文件中的描述。

按照实际情况修改 发行注记 文件 chapter00/0.1-release.md 和 贡献指南  chapter00/0.2-contribution.md 的内容。


## 配置

请按照自己的实际情况修改 `book.json` 文件中的配置中的作者信息等内容。

## 发布

在根目录下有一个 `action.sh` 的 shell 脚本，执行这个脚本就可以发布 GitBook 书籍到 GitHub Pages 的 docs 目录中，可以通过网页浏览了。

PS：当然，要现在GitHub Pages 中配置主分支的 docs 目录作为静态页面的路径。

如果遇到问题请提 Issue 或者发邮件。

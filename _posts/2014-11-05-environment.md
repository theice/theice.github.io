---
layout: post
categories: [article]
title: "合作者环境搭建说明"
tags: [开发环境]
---

### 说明

坤鹏请参考这个文件自行搭建环境。你们把这个平台都熟悉运用起来后，我会带着你们一起学习其他流行的IT技术(第一个技术暂定Android，如有疑问，私下解决。)，并在GitHub上创建另外的项目进行实战。

搭建这个环境的目的是把它作为一个平台，记录以后学习的技术，积累学到的知识点。

----------

#### 1. 配置Jekyll环境，便于本地预览效果

本来想写个图文教程的，但是后来发现有个网站[jekyll-windows](http://jekyll-windows.juthilo.com/)介绍的很清楚了，请务必按照网站说明的顺序及流程把**所有提到的软件**都安装好。安装好后最好简单熟悉一下Jekyll，参考[官网](http://jekyllrb.com/)即可。

#### 2. 安装配置Git环境

***安装Git***
有以下两种方法，可以任选其一安装，也可以都安装：

- [msysgit官网](http://msysgit.github.io/)直接下载安装，记得把“Git Bash”和“Git GUI”加入右键菜单，方便以后使用。
- [GitHub for windows](https://windows.github.com/)，参照说明安装即可。这个软件包含了一套git环境和github客户端。

***配置Git***

如果安装的是msysgit，运行git bash用ssh方式操作git仓库时需要启动ssh-agent，请参考[Working with SSH key passphrases](https://help.github.com/articles/working-with-ssh-key-passphrases/#auto-launching-ssh-agent-on-msysgit)设置ssh key，默认路径在：

```/<用户目录>/.ssh/id_rsa.pub```

如果安装的是GitHub for windows，则运行程序时会自动生成ssh key，路径在：

```/<用户目录>/.ssh/github_rsa.pub```

这步操作注意记下生成的ssh key公钥，然后私下发给我。

Git环境配置好后，开始自行学习简单的git操作，请参考[Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)，最好把里面的操作都练习一下。

#### 3. checkout代码至本地，并实验发布博文

以上任务都完成后，开始实际操作，先注册[GitHub](http://github.com/)账号，这个账号也私下发给我，然后克隆[本博的仓库](https://github.com/theice/theice.github.io)至本地，然后在git bash命令行下运行:

```
jekyll serve
```

可以启动本地服务，然后打开浏览器，访问：[本地博客](http://localhost:4000/)，应该可以看到和本博内容一样的页面。

至此环境搭建完成，开始学习发布博客，本博客使用Markdown语言，可根据[参考文档](http://daringfireball.net/projects/markdown/syntax)自行学习。

以上都没问题后，给你们的第一个任务来了：使用自己熟悉的文本编辑器（推荐Notepad++）编写第一篇博文，然后使用Git发布出来。
**注意**，Jekyll使用无BOM头的UTF-8编码来生成博客内容，所以一定要注意发布文章的编码格式。

#### 4. 备注

遇到问题，自行Google或者Baidu，最好能直接从官方文档处获取帮助，如果问题还没有解决，请在本页下面评论处提问，或是下次见面当面解决。

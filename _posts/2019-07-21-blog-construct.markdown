# 基于GitHub Pages搭建一个Blog #

----------
解决的问题：

1. 如何在 GitHub 上搭建一个博客框架？
2. 如何 Post 第一个博客？


需要的元素：

1. 安装 Git 工具
2. 创建一个 GitHub 账号

下面就开始我们的博客搭建之旅吧;)

**#1 如何在 GitHub 上搭建一个博客框架？**

- 创建一个git仓库 (注意: 仓库名格式为 user_name.github.io)

![创建一个git仓库](/assets/CreateRepository.jpg)

- 为了降低搭建难度，建议 fork 别人在GitHub上已搭建的博客加以改进或者在[Jekyll模板站点](http://jekyllthemes.org/)下载自己喜欢的模板

![创建一个git仓库]({{ site.url }}/assets/DownloadTemplate.jpg)

- 把你创建的空 repository 或 fork 的 repository 克隆到本地

    $ git clone https://github.com/user_name/user_name.github.io

![创建一个git仓库]({{ site.url }}/assets/RepositoryClone.jpg)

- 若采用下载模板的方式则将下载的.zip文件解压缩到克隆的本地 git 仓库中

为了更强的获得感，此部分以Jekyll模板网站的一个简洁模板为例介绍如何搭建一个博客框架，后续可以自己丰富 Blog 的内容，体验一点点美化自己博客的过程. (如果fork别人的博客请跳过此部分)

    $ cd <username>.github.io
	$ git add --all
    $ git commit -m "Init commit"
    $ git push origin master
    
打开博客网站https://<username>.github.io 测试是否有效

**#2 如何 Post 第一个博客？**

进入本地 _posts 目录，在里面新添加一个文件，命名格式：

yyyy-mm-dd-name.markdown

例如：2019-07-21-blog-construct.markdown

windows用户可下载MarkdownPad进行博客书写，该软件提供实时预览功能，有助于随时调整格式

书写完毕后将本地修改推送到远 GitHub 仓库即可

Good job！你已完成博客框架的搭建以及第一篇博文的推送


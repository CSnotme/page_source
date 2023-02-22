---
title: hexo+github+noteshub在线文档
date: 2023-02-22 10:27:53
tags:
---
---
# 1.安装hexo
- git安装
```
https://git-scm.com/
```
- nodejs安装
```
https://nodejs.org/en/download/
```
- hexo安装
```
https://hexo.bootcss.com/docs/index.html
```
- 查看依赖是否安装
![查看依赖是否安装.png](https://github.com/CSnotme/source/raw/main/_posts/2023-02-22-hexo-github-noteshub%E5%9C%A8%E7%BA%BF%E6%96%87%E6%A1%A3/%E6%9F%A5%E7%9C%8B%E4%BE%9D%E8%B5%96%E6%98%AF%E5%90%A6%E5%AE%89%E8%A3%85.png "查看依赖是否安装.png")

---
# 2.创建github pages
- 新建github仓库
![新建github仓库.jpg](https://github.com/CSnotme/source/raw/main/_posts/2023-02-22-hexo-github-noteshub%E5%9C%A8%E7%BA%BF%E6%96%87%E6%A1%A3/git%E6%96%B0%E5%BB%BA%E4%BB%93%E5%BA%93.jpg)
- 设置github开启pages
![设置github开启pages.jpg](https://github.com/CSnotme/source/raw/main/_posts/2023-02-22-hexo-github-noteshub%E5%9C%A8%E7%BA%BF%E6%96%87%E6%A1%A3/git%E5%BC%80%E5%90%AFpages.jpg)
- 配置hexo推送github地址
![配置hexo推送的git地址.png](https://github.com/CSnotme/source/raw/main/_posts/2023-02-22-hexo-github-noteshub%E5%9C%A8%E7%BA%BF%E6%96%87%E6%A1%A3/%E9%85%8D%E7%BD%AEhexo%E6%8E%A8%E9%80%81%E7%9A%84git%E5%9C%B0%E5%9D%80.png "配置hexo推送的git地址.png")

---
# 3. 使用NotesHub
官网 https://www.noteshub.app/
- 新建一个git仓库，存放hexo中的source文件夹中的源内容
- NotesHub关联git仓库，即可编译source中的markdown文件
![nodeshub关联github.jpg](https://github.com/CSnotme/source/raw/main/_posts/2023-02-22-hexo-github-noteshub%E5%9C%A8%E7%BA%BF%E6%96%87%E6%A1%A3/nodeshub%E5%85%B3%E8%81%94github.jpg "nodeshub关联github.jpg")
- 编辑内容保存后会自动推送到source库中，从hexo的source中拉取github最新修改，然后在生产静态文件推送博客
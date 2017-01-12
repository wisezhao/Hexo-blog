---
title: README
date: 2017-01-06 15:03:00
tags:
---

**准备工作:**
- Hexo: 基于Node的一个静态博客框架，可以方便生成静态网页托管在github上
- node,js : 用来生成静态页面。 Node.js[官网][1]下载
- git :本地数据提交至github
- github : 博客的远程仓库，备份数据

<!-- more -->

  **安装:**
 - 安装Node.js
 - 安装Hexo
	 - npm install -g hexo 
	 - hexo init  ( 初始化)
	 - npm install 
	 - hexo s
	  
**功能安装：**
-  阅读统计量
	- [参考链接][2]
	- 配置LeanCloud
	- 修改Next主题_config.yml  中的 `busuanzi_count:  enable :true`
- 多说评论 
	- [参考链接][3] 
- Github自动备份博客源文件
	- [参考链接][4]
- 文章在网页显示
	- [参考链接][5]
- 增加主菜单
	- [参考链接][6]
	- [菜单图标参考链接][7]
	- 主题配置_config.yml 中`#Menu Settings` 添加 菜单，如：`event: /event/event.html`
	- 菜单图标：`menu_icons:`
	- 菜单文字：`zh-Hans.yml`



**备份说明**

 - 博客数据备份于github上的Hexo-blog
 - 定期更新Next主题， 目录中Next为一个git仓库

  [1]: https://nodejs.org/en/
  [2]: https://notes.wanghao.work/2015-10-21-%E4%B8%BANexT%E4%B8%BB%E9%A2%98%E6%B7%BB%E5%8A%A0%E6%96%87%E7%AB%A0%E9%98%85%E8%AF%BB%E9%87%8F%E7%BB%9F%E8%AE%A1%E5%8A%9F%E8%83%BD.html
  [3]: http://theme-next.iissnan.com/third-party-services.html#duoshuo
  [4]: https://notes.wanghao.work/2015-07-06-%E8%87%AA%E5%8A%A8%E5%A4%87%E4%BB%BDHexo%E5%8D%9A%E5%AE%A2%E6%BA%90%E6%96%87%E4%BB%B6.html
  [5]: http://theme-next.iissnan.com/faqs.html
  [6]: http://theme-next.iissnan.com/getting-started.html#menu-settings
  [7]: http://www.fontawesome.cn/
  [8]: http://ojiqvr961.bkt.clouddn.com/%E4%B8%80%E7%94%9F%E6%9C%89%E4%BD%A0-%E5%8F%AF%E5%8F%AF_%E6%9C%80%E7%BB%88%E7%89%8820161118.mp4
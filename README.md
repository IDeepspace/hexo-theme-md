##  Hexo-theme-md

> 一款基于 `material design` 的 `hexo` 主题 —— Hexo-theme-md

#### 一、下载安装

打开终端，`cd` 到你博客的路径，下载主题到 `themes/` 文件夹：

```shell
$ git clone https://github.com/IDeepspace/hexo-theme-md.git
```

#### 二、配置主题

```yaml
# 配置菜单导航的名称、路径和图标icon.
menu:
  首页:
    url: /
    icon: fa-home
  标签:
    url: /tags
    icon: fa-tags
  分类:
    url: /categories
    icon: fa-bookmark
  归档:
    url: /archives
    icon: fa-archive
  关于:
    url: /about
    icon: fa-user-circle-o

# 配置网站favicon和网站LOGO
favicon: /favicon.png
logo:

# 是否激活文章 TOC 功能，并配置TOC支持选中哪些标题类型.
toc:
  enable: true
  heading: h2, h3, h4

# 是否激活文章末尾的打赏功能，默认激活（替换为的你自己的微信、支付宝二维码图片）.
reward:
  enable: true
  title: 请我喝杯咖啡?
  wechat: /medias/reward/wechat.png
  alipay: /medias/reward/alipay.png

# 在"关于"页面中配置个人信息，包括头像、职业和个人介绍.
profile:
  avatar: /medias/avatar.png
  career: 软件开发工程师
  introduction: 凡事预 ？立 ：废

# 在 "关于" 页面配置 "我的项目" 信息
myProjects:
  enable: true
  data:
    hexo-theme-md:
      icon: fa-umbrella
      iconBackground: 'linear-gradient(to bottom right, #66BB6A 0%, #81C784 100%)'
      url: https://github.com/IDeepspace/hexo-theme-md
      desc: hexo 主题

# 在 "关于" 页面配置 "我的技能" 信息
mySkills:
  enable: true
  data:
    Java:
      background: 'linear-gradient(to right, #FF0066 0%, #FF00CC 100%)'
      percent: 85%
    JavaScript:
      background: 'linear-gradient(to right, #9900FF 0%, #CC66FF 100%)'
      percent: 95%
    HTML5:
      background: 'linear-gradient(to right, #2196F3 0%, #42A5F5 100%)'
      percent: 95%
    CSS:
      background: 'linear-gradient(to right, #00BCD4 0%, #80DEEA 100%)'
      percent: 95%
    SQL:
      background: 'linear-gradient(to right, #4CAF50 0%, #81C784 100%)'
      percent: 85%
    React:
      background: 'linear-gradient(to right, #181698 0%, #81C784 100%)'
      percent: 90%
    Ruby:
      background: 'linear-gradient(to right, #2196F3 0%, #81C784 100%)'
      percent: 80%
    程序设计:
      background: 'linear-gradient(to right, #FFEB3B 0%, #FFF176 100%)'
      percent: 75%

# 在 "关于" 页面配置 "我的相册" 图片
myGallery:
  enable: true
  data:
    - /medias/featureimages/winter.jpg
    - /medias/featureimages/saguenayIceFishing.jpg
    - /medias/featureimages/sun.jpg

# 设置在归档页面中是否显示 "文章日历" 控件
postCalendar: true

# Gitalk 评论模块的配置，默认为不激活
gitalk:
  enable: false
  owner:
  repo:
  oauth:
    clientId:
    clientSecret:
  admin:
    -

# Gitment 评论模块的配置，默认为不激活
gitment:
  enable: false
  owner:
  repo:
  oauth:
    clientId:
    clientSecret:

# Disqus评论模块的配置，默认为不激活
disqus:
  enable: false
  shortname:

# Livere 来必力评论模块的配置，默认为不激活
livere:
  enable: false
  uid:

# 配置是否在 header 中显示 fork me on github 的图标，默认为true，你可以修改为你的仓库地址.
githubLink:
  enable: true
  url: https://github.com/IDeepspace
  title: Fork Me

# 无文章特色图片时需要显示的文章特色图片.
featureImages:
  - /medias/featureimages/winter.jpg

postBackgroundImage:
  - /medias/featureimages/winter.jpg
```
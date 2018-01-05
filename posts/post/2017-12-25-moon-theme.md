---
layout: post
title:  "Moon Jekyll Theme"
date:   2017-12-25
excerpt: "Minimal, one column Jekyll theme for your blog."
project: true
tag:
- jekyll 
- moon
- blog
- about
- theme
comments: true
---

![Moon Homepage](https://cloud.githubusercontent.com/assets/754514/14509720/61c61058-01d6-11e6-93ab-0918515ecd56.png)    
    
<center><b>Moon</b> is a minimal, one column jekyll theme.</center>
     
 我不是开发人员或设计人员。我不添加脚注来显示谁做了这个主题。如果你喜欢这个主题或者使用它，请给我一个* ** * *来激励我，这让我很开心。
<iframe src="https://ghbtns.com/github-btn.html?user=TaylanTatli&repo=Moon&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>    
      
## 安装
* Fork 这个 [Moon repo](https://github.com/TaylanTatli/Moon/fork)
* 编辑 `_config.yml` file.
* 移除文件 `_posts` folder and add yours.
* 编辑 `index.md` file in `about` folder.
* 改变名称`YourUserName.github.io`     
That's all.

## Preview

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509716/61ac6c8e-01d6-11e6-879f-8308883de790.png
	https://cloud.githubusercontent.com/assets/754514/14509717/61ad05ae-01d6-11e6-85ae-5a817dd8763b.png
	https://cloud.githubusercontent.com/assets/754514/14509714/61a89708-01d6-11e6-8fcd-74b002a060df.png
{% endcapture %}
{% include gallery images=images caption="Screenshots of Moon Theme" cols=3 %}

---

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509718/61b09a20-01d6-11e6-8da1-4202ae4d83cd.png
	https://cloud.githubusercontent.com/assets/754514/14509715/61aa9d00-01d6-11e6-81a6-c6837edf2e84.png
{% endcapture %}
{% include gallery images=images caption="Moon Theme on Small Screen Size" cols=2 %}      
      
See a [live version of Moon](http://taylantatli.github.io/Moon) hosted on GitHub.      

## 网站设置
快速检查一下你想要编辑的文件，然后开始运行。

### 网站广泛配置
`_config.yml` 是你的朋友。打开它，个性化它。大多数变量都是自解释的，但如果需要的话，这里有一个解释:
#### title

你的网站的标题…骇人的!

例如 `title: My Awesome Site`

#### 博客

在你的主页上显示的描述。

####  描述
用于meta标记和导航菜单的描述。

#### url

用于在“站点地图”中生成绝对url。xml”、“饲料。xml '，并在' '中生成规范url。当在本地开发时，可以将其注释掉或者使用类似于“http://localhost:4000”这样的内容，这样所有的资产都可以正常地加载。*不要包含拖尾的“/”*。

例子:

{% highlight yaml %}
url: http://taylantatli.me/Moon
url: http://localhost:4000
url: //cooldude.github.io
url:
{% endhighlight %}

#### 阅读时间

设置正确显示文章的阅读时间。设置“words_per_minute”，默认为200。

#### 标志
你的网站的标志。它将在主页和导航菜单上显示。也用于twitter的元标签。

#### 背景
图像的背景。如果你不设置它，颜色将被用作背景。

#### 55/5000  
谷歌分析和网站管理员工具

Google Analytics UA and Webmaster Tool verification tags can be entered in `_config.yml`. For more information on obtaining these meta tags check [Google Webmaster Tools](http://support.google.com/webmasters/bin/answer.py?hl=en&answer=35179) and [Bing Webmaster Tools](https://ssl.bing.com/webmaster/configure/verify/ownership) support.

#### MathJax
这是启用。但如果你不想使用它。设置错误的 `_config.yml`.

#### Disqus Comments

在 `_config.yml`中设置disqus短名称。yml使用注释。

---

### 导航链接

要设置在顶部导航编辑`_data/navigation.yml`中出现的链接。使用以下格式设置URL和标题的链接，如你所愿。*外部链接将在新窗口中打开。

{% highlight yaml %}
- title: Home
  url: /

- title: Blog
  url: /blog/

- title: Projects
  url: /projects/

- title: About
  url: /about/

- title: Moon
  url: http://taylantatli.me/Moon
{% endhighlight %}

---

## 布局和内容

月亮主题使用(https://github.com/penibelst/jekyll-compress-html)压缩html输出。但是如果使用“linenos”，它会导致错误。我建议不要用行号来编码，因为这个主题看起来不太好，我也没有给他们一个合适的样式。如果您坚持使用行号，只需删除“布局:从布局压缩”字符串。它将禁用压缩。

### 特征图像

您可以设置每个帖子的特征图像。添加“功能:一些链接”到你的帖子的前端。

```
feature: /assets/img/some-image.png
or
feaure: http://example.com/some-image.png
```    
 这也将用于推特:

![Moon Twitter Card](https://cloud.githubusercontent.com/assets/754514/14509719/61c5751c-01d6-11e6-8c29-ce8ccad149bf.png)

### 评论
为你的帖子显示评论，添加“评论:真实”到你的帖子的前沿问题。

---

## 出现问题了吗?

发现了一个bug或者不确定某样东西是如何工作的?通过各种方法 [file a GitHub Issue](https://github.com/TaylanTatli/Moon/issues/new). And if you make something cool with this theme feel free to let me know.

---

## 许可证

这个主题是免费的开源软件，在MIT的许可下发布。所以在你的网站上可以自由使用这个Jekyll主题，而不需要链接到我或包含一个免责声明。

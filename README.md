# Hexo theme | Sagittarius

![](http://img.social/2020/10/09/26f625336a951.png)


---
## 介绍 | introduce
``Sagittarius``是一个简洁大方的``hexo``主题，由[SDLTF](https://sdltf.info)开发。欢迎您的使用！

QQ群：1161431755

## 使用 | use
和其他的主题一样，您可以使用``git clone``使用这个主题

```git
git clone https://github.com/SDLTF/hexo-theme-Sagittarius.git themes/Sagittarius
```

然后在博客根目录的``_config.yml``下编辑：
```yml
themes: Sagittarius
```

# 配置与特性 | setting & feature

本主题的``_config.yml``如下
```yml
# 网站语言
language: zh-CN

# main menu navigation
menu:
  📖主页: /
  ⏰归档: /archives/
  📂分类: /categories/
  🔖标签: /tags/
  🔗链接: /links/
  👁‍🗨关于: /about/
  📦知乎: https://www.zhihu.com/people/ltf-70-2

# 网站标题&博客标题
website_title: 'SDLTF'
blog_title: 'SDLTF'
blog_title_size: 36px;

# feature：不同页面的标题
home: '📖主页'
archive: '⏰归档'
tag: '🔖标签'
link: '🔗链接'
categorie: '📂分类'
about: '👁‍🗨关于'

# 主题色&导航栏背景
custom_color: 'rgb(0,122,204)'
toplab_background_color: 'rgba(255,255,255,0.8)'

# 背景图轮播
background_image:
  enable: true
  img_list:
    - http://img.social/2020/10/09/f7bff356b2e23.png
    - http://img.social/2020/10/09/7a83d5914ff4d.png
    - http://img.social/2020/10/09/f3460e81fcad0.png
    - http://img.social/2020/10/21/e3359414310ac.png
    - http://img.social/2020/10/21/84290a3c42d52.png
    - http://img.social/2020/10/21/760a4ec3076e3.png
    - http://img.social/2020/10/21/fcc71bdaf6f28.png
    - http://img.social/2020/10/21/fcc71bdaf6f28.png
    - http://img.social/2020/10/21/00574c4bb2b27.png
    
# feature：右侧公告栏
right_ad:
  enable: false

# stylesheets loaded in the <head>
stylesheets:
- /css/Sagittarius.css

# scripts loaded in the end of the body
scripts:
- /js/Sagittarius.js

```

本主题还未完成的功能：

-[] ``archives``，``categories``，``tag``页面的渲染
-[] 更丰富的选择
-[] ``lazy load``
-[] ``highlight`` 代码高亮
-[] ``Gitalk``、``Valine``、畅言 评论
-[] ``FancyBox`` 图片灯箱
-[] ``LeanCloud`` 统计访问量
-[] 支付宝、微信 打赏
-[] 相册页面，图片支持瀑布流加载
-[] 格言，可配合插件 hexo-plug-motto 实现动态格言
-[] 百度、CNZZ、谷歌 站长统计 及 SEO优化
-[] 定制 主题风格、CDN、埋点脚本、社交链接、版权说明 等


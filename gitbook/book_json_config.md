# book.json配置文件

```
{
  "title": "demo",//标题
  "description": "demo",//文档描述
  "language": "zh",//选择编辑的语言环境
  "plugins": [ //引入需要的插件，前面有-号的为uninstall相应的插件
    "disqus",
    "github",
    "editlink",
    "prism",
    "-highlight",
    "baidu",
    "splitter",
    "sitemap",
    "tbfed-pagefooter",
    "fontsettings",
    "simple-page-toc",
    "links"
  ],
  "styles": {
    "website": "styles/website.css" //引入css文件进行css样式的修改
  },
  "pluginsConfig": {
       "tbfed-pagefooter": {
            "copyright": "",
            "modify_label": "该文件修订时间：",
            "modify_format": "YYYY-MM-DD HH:mm:ss"
        },//显示文件的修改事件，包括一些版权声明
        "fontsettings": {
            "theme": "white",
            "family": "serif",
            "size": 12
        },//显示样式以及文字大小的主题
        "simple-page-toc": {
            "maxDepth": 3,
            "skipFirstH1": true
        },//<!-- toc -->中放置代码注释。生成GitBook以后，此评论会立即插入content
       //使用深度最多为maxdepth的标题。排除文件中的第一个h1级标题。
        "links": {
            "gitbook": false,
            "sharing": {
                "google": false,
                "facebook": false,
                "twitter": false,
                "all": false
        },//默认的一些分享的展示与隐藏，true为展示，false为隐藏
    "disqus": {
      "shortName": "webpack-handbook"//生成评论的插件
    },
    "github": {
      "url": "https://github.com/webChatContact/baas-v2-help"
    },
    "editlink": {
      "base": "https://github.com/webChatContact",
      "label": "编辑本页面"//内容顶部显示 编辑本页 链接。
    },
    "baidu": {
        "token": "a9787f0ab45d5e237bab522431d0a7ec"//使用百度统计。
    },
    "sitemap": {
        "hostname": "http://baidu.com/"//生成站点地图
    }
  }
}
```


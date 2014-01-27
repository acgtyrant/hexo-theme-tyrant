tyrant
=========

Another [Hexo](http://zespia.tw/hexo/) Theme.

[demo](http://arch.acgtyrant.com)

![](https://lh6.googleusercontent.com/-cZeS5x1qVp4/UuZn27upVuI/AAAAAAAAE5M/ltY9YwPbodk/w971-h546-no/ScreenShot.png)

## Install

Execute the following command and modify `theme` in `_config.yml` to `tyrant`.

```
git clone git://github.com/acgtyrant/hexo-theme-tyrant.git themes/tyrant
```

## Update

Execute the following command to update tyrant.

```
cd themes/tyrant
git pull
```

## Notes

### Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives
  About: /about
  RSS: atom.xml

widgets:
- search
- category
- recent_posts
- tag

excerpt_link: Read More

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: false
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

fancybox: true

google_analytics:
rss: /atom.xml
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

### RSS

There is a `RSS` page in the theme, so you should install the hexo-generator-feed following the [manual][4] or remove `RSS: /atom.xml` & `rss: /atom.xml` in `theme/tyrant/_config.yml`.

### Favicon
If you are going to use favicon then you should use the ico format, there are two benefits:

1. Many website which make favicon alaways create ico format's favicon.
2. The `ico` format supports Retina display.

You can use [faviconer][1] to create simple favicon, or read [How to Create Retina-Caliber Favicons][2].  

After getting the favicon, put it in the `source` (**not** that `theme/tyrant/source`!) and excute these:

    hexo generate
    hexo deploy
    
Done.

中文用戶可直接閱讀 [Favicon 二三事][3]。

## Features

### Gallery Post

![](http://i.minus.com/ibp6Hbytwgof9y.jpg)

```
---
layout: photo
title: Gallery Post
photos:
- http://i.minus.com/ibobbTlfxZgITW.jpg
- http://i.minus.com/iedpg90Y0exFS.jpg
---
```

### Link Post

![](http://i.minus.com/i7hBbGqh14EWo.png)

```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```

### Tweet Widget

![](http://i.minus.com/iMC8EyF9y0Y3y.PNG)

### Fancybox

![](http://i.minus.com/iHv7h7rZNqHvo.PNG)

[Hexo]: http://zespia.tw/hexo/
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/

## Thanks

This theme is modified based on [light](https://github.com/tommy351/hexo-theme-light), the hexo default theme.

Thank the creator [tommy351][5] and the other [contributors][6] very much!


  [1]: http://www.faviconer.com/
  [2]: http://daringfireball.net/2013/01/retina_favicons
  [3]: http://tsgzj.me/2013/03/11/something-about-favicon/
  [4]: https://github.com/tommy351/hexo/wiki/Plugins
  [5]: https://github.com/tommy351
  [6]: https://github.com/acgtyrant/hexo-theme-tyrant/graphs/contributors

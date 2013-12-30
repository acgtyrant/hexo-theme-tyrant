tyrant
=========

Another [Hexo](http://zespia.tw/hexo/) Theme.

[demo](http://arch.acgtyrant.com)

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

### RSS

There is a `RSS` page in the theme, so you should install the hexo-generator-feed following the [manual][4] or remove `RSS: /atom.xml` & `rss: /atom.xml` in `theme/tyrant/_config.yml`.

## Thanks

This theme is modified based on [light](https://github.com/tommy351/hexo-theme-light), the hexo default theme.

Thank the creator [tommy351][5] and the other [contributors][6] very much!


  [1]: http://www.faviconer.com/
  [2]: http://daringfireball.net/2013/01/retina_favicons
  [3]: http://tsgzj.me/2013/03/11/something-about-favicon/
  [4]: https://github.com/tommy351/hexo/wiki/Plugins
  [5]: https://github.com/tommy351
  [6]: https://github.com/acgtyrant/hexo-theme-tyrant/graphs/contributors

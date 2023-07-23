Hexo theme: Apollo - yuseiito flavord
=================

hexo theme "Apollo" をyuseiitoが自身のblog向けに改変したものです。

歴史的には、どうやらSANOGRAPHIX氏がTumblr themeとして作成したもの(MITライセンス) が
[オリジナル](https://github.com/sanographix/tumblr/tree/master/apollo) であり、
次いで [Hexoに移植された](https://github.com/joyceim/hexo-theme-apollo.git)ようです。
しかしながら、2023年7月現在joyceim氏のアカウントは消失しています。

本テーマ自体は、[AthenaYin氏のバージョン](https://github.com/AthenaYin/hexo-theme-apollo) からforkして、
日本語が中華フォントでレンダリングされるのを防ぐなどの改変を加えています。


##Installation

###Install

``` bash
$ git clone git@github.com:yuseiito/hexo-theme-apollo.git themes/apollo
```

**Apollo requires Hexo 2.4 and above.**

###Update

``` bash
cd themes/apollo
git pull
```

##Configuration

``` yml
# Header
menu:
    Home: /
    Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox](http://fancyapps.com/fancybox/)
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path

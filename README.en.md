# NexT

> NexT is a high quality elegant [Jekyll](https://jekyllrb.com) theme ported from [Hexo NexT](https://github.com/iissnan/hexo-theme-next). It is crafted from scratch, with love.


 * [Live Preview](http://simpleyyt.github.io/jekyll-theme-next/)
 * [Yitao's Blog](http://simpleyyt.github.io)

## Screenshots

* Desktop
![Desktop Preview](https://github.com/hi2t/Blog.picture/blob/master/jenkins/homepage.png?raw=true)

* Sidebar

![Desktop Sidebar Preview](https://github.com/hi2t/Blog.picture/blob/master/jenkins/settingpage.png?raw=true)

* Sidebar (Post details page)

![Desktop Sidebar Preview](https://github.com/hi2t/Blog.picture/blob/master/jenkins/creatpage.png?raw=true)

* Mobile

![Mobile Preview](http://iissnan.com/nexus/next/mobile.png)

*Not yet
![not yet](https://github.com/hi2t/Blog.picture/blob/master/mac/haven't.png?raw=true)

*done
![done](https://github.com/hi2t/Blog.picture/blob/master/mac/done.png?raw=true)

*have
![have](https://github.com/hi2t/Blog.picture/blob/master/mac/have.png?raw=true)

*wifi01
![wifi01](https://github.com/hi2t/Blog.picture/blob/master/charles/wifi01.png?raw=true)

*wifi02
![wifi02](https://github.com/hi2t/Blog.picture/blob/master/charles/wifi02.png?raw=true)

*wifi03
![wifi03](https://github.com/hi2t/Blog.picture/blob/master/charles/wifi03.png?raw=true)

*wifidone
![wifidone](https://github.com/hi2t/Blog.picture/blob/master/charles/wifidone.png?raw=true)


## Installation

Check whether you have `Ruby 2.1.0` or higher installed:

```sh
ruby --version
```

Install `Bundler`:

```sh
gem install bundler
```

Clone Jacman theme:

```sh
git clone https://github.com/Simpleyyt/jekyll-theme-next.git
cd jekyll-theme-next
```

Install Jekyll and other dependencies from the GitHub Pages gem:

```sh
bundle install
```

Run your Jekyll site locally:

```sh
bundle exec jekyll server
```

More Details：[Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)


## Features

### Multiple languages support, including: English / Russian / French / German / Simplified Chinese / Traditional Chinese.

Default language is English.

```yml
language: en
# language: zh-Hans
# language: fr-FR
# language: zh-hk
# language: zh-tw
# language: ru
# language: de
```

Set `language` field as following in site `_config.yml` to change to Chinese.

```yml
language: zh-Hans
```

### Comment support.

NexT has native support for `DuoShuo` and `Disqus` comment systems.

Add the following snippets to your `_config.yml`:

```yml
duoshuo:
  enable: true
  shortname: your-duoshuo-shortname
```

OR

```yml
disqus_shortname: your-disqus-shortname
```

### Social Media

NexT can automatically add links to your Social Media accounts:

```yml
social:
  GitHub: your-github-url
  Twitter: your-twitter-url
  Weibo: your-weibo-url
  DouBan: your-douban-url
  ZhiHu: your-zhihu-url
```

### Feed link.

> Show a feed link.

Set `rss` field in theme's `_config.yml`, as the following value:

1. `rss: false` will totally disable feed link.
2. `rss:  ` use sites' feed link. This is the default option.

    Follow the installation instruction in the plugin's README. After the configuration is done for this plugin, the feed link is ready too.

3. `rss: http://your-feed-url` set specific feed link.

### Up to 5 code highlight themes built-in.

NexT uses [Tomorrow Theme](https://github.com/chriskempson/tomorrow-theme) with 5 themes for you to choose from.
Next use `normal` by default. Have a preview about `normal` and `night`:

![Tomorrow Normal Preview](http://iissnan.com/nexus/next/tomorrow-normal.png)
![Tomorrow Night Preview](http://iissnan.com/nexus/next/tomorrow-night.png)

Head over to [Tomorrow Theme](https://github.com/chriskempson/tomorrow-theme) for more details.

## Configuration

NexT comes with few configurations.

```yml

# Menu configuration.
menu:
  home: /
  archives: /archives

# Favicon
favicon: /assets/favicon.ico

# Avatar (put the image into next/source/images/)
# can be any image format supported by web browsers (JPEG,PNG,GIF,SVG,..)
avatar: /assets/default_avatar.png

# Code highlight theme
# available: normal | night | night eighties | night blue | night bright
highlight_theme: normal

# Fancybox for image gallery
fancybox: true

# Specify the date when the site was setup
since: 2013

```

## Browser support

![Browser support](http://iissnan.com/nexus/next/browser-support.png)

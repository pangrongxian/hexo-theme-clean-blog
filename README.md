# Clean Blog Hexo

![](http://www.codeblocq.com/img/hexo-theme-thumbnail/CleanBlog.png)

Hexo implementation of [Clean Blog](http://blackrockdigital.github.io/startbootstrap-clean-blog/index.html)

Clean blog is a full featured, responsive Hexo theme. [Demo here](http://www.codeblocq.com/assets/projects/hexo-theme-clean-blog/).

## Features

- Disqus and Facebook comments
- Google Analytics
- Cover image for posts and pages
- Tags and Categories Support
- Responsive Images
- Image Gallery
- Code syntax highlighting

## External libraries used

- [Bootstrap](http://getbootstrap.com/css/)
- [FeatherLight.js](http://noelboss.github.io/featherlight/) (Gallery)
- [jQuery](https://jquery.com/)

## Installation

```
$ git clone https://github.com/klugjo/hexo-theme-clean-blog.git themes/clean-blog
```

Then update your blog's main `_config.yml` to set the theme to `clean-blog`:

```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: clean-blog
```

## Configuration

### Menu

The menu is configured in the theme's `_config.yml`.

```
# Header
menu:
  Home: /
  Archives: /archives
```

The object key is the label and the value is the path.

### Top Left Label

The top left label is configured in the theme's `_config.yml`. When clicked it will lead to the Home Page.

```
# Title on top left of menu. Leave empty to use main blog title
menu_title: Configurable Title
```

### Home Page cover image

The Home Page cover is configured in the theme's `_config.yml`. It will be the same for all index type pages.

```
# URL of the Home page image
index_cover: /img/home-bg.jpg
```

### Default post title

The default post title (used when no title is specified) is configured in the theme's `_config.yml`.

```
# Default post title
default_post_title: Untitled
```

### Comments

The comments provider is specified in the theme's `_config.yml`. If you specify both a `disqus_shortname` and a `facebook.appid` there will be 2 sets of comment per post. So choose one.

```
# Comments. Choose one by filling up the information
comments:
  # Disqus comments
  disqus_shortname: klugjotest
  # Facebook comments
  facebook:
    appid: 123456789012345
    comment_count: 5
    comment_colorscheme: light
```

### Google Analytics

The Google Analytics Tracking ID is configured in the theme's `_config.yml`.

```
# Google Analytics Tracking ID
google_analytics:
```

### Social Account

Setup the links to your social pages in the theme's `_config.yml`. Links are in the footer.

```
# Social Accounts
twitter_url:
facebook_url:
github_url: https://github.com/klugjo/hexo-theme-clean-blog
```

### Author

The post's author is specified in the posts front-matter:

```
author: Klug Jo
---
```

### Post's Cover Image

By default, posts will use the home page cover image. You can specify a custom cover in the front-matter:

```
cover: /assets/contact-bg.jpg
```

## Creator

This theme was created by [Blackrock Digital](https://github.com/BlackrockDigital) and adapted for Hexo by [Jonathan Klughertz](http://www.codeblocq.com/).

## License

MIT

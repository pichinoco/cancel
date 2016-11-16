# Tranquilpeak

A gorgeous responsive theme for Hugo blog framework.

![Tranquilpeak](https://raw.githubusercontent.com/kakawait/hugo-tranquilpeak-theme/master/showcase.png)

## Alpha/Beta versions

**ATTENTION** during *alpha* or *beta* [versions](https://github.com/kakawait/hugo-tranquilpeak-theme/milestones) breaking changes are possible on config file.

You can track [breaking changes label](https://github.com/kakawait/hugo-tranquilpeak-theme/issues?q=is%3Aissue+is%3Aopen+label%3A%22breaking+changes%22) or simply read [CHANGELOG.md](https://github.com/kakawait/hugo-tranquilpeak-theme/CHANGELOG.md).

Moreover you can use `migrators` from `migrators` folders. Migration scripts will produces a new config file with suffix `.new`, it will not override your current config. Indeed migration scripts will erase any comments and formating, that why migration scripts will not override your config.

Any modifications are printed on output to allow you reproduce/replay migrations on your own config file manually.

## Credits

*Hugo* version of Tranquilpeak is a based on original *Hexo* version https://github.com/LouisBarranqueiro/hexo-theme-tranquilpeak. This version is simply a port to *Hugo* static site generator.

Please all the credit should be attributed to [original *Hexo* version](https://github.com/LouisBarranqueiro/hexo-theme-tranquilpeak) and its author [Louis Barranqueiro](https://github.com/LouisBarranqueiro).

*Hugo* version keeps every `.js` and `.css` files untouched from original *Hexo* version in order to enjoy futur original *Hexo* version updates or features! 

## Summary

- [General](#general)
- [Features](#features)
- [Quick start](#quick-start)
- [Demo](#demo)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Showcase](#showcase)
- [License](#license)

## General

- **Authors**: [Louis Barranqueiro (LouisBarranqueiro)](https://github.com/LouisBarranqueiro) and [Thibaud Leprêtre (kakawait)](https://github.com/kakawait)
- **Version**: 0.1.3-ALPHA (based on Hexo version 1.9.1)
- **Compatibility**: Hugo v0.17

## Features

**General features:**  

- Fully responsive
- Optimized for tablets & mobiles
- Configurable menu of the sidebar
- Pages to filter tags, categories and archives
- Background cover image
- Beautiful about page
- Support Open Graph protocol
- Easily customizable (fonts, colors, layout elements, code coloration, etc..)
- Documentations
  
**Posts features:**  

- Thumbnail image
- Cover image
- Responsive videos & images
- Sharing options
- Navigation menu
- GitHub theme for code highlighting (customizable)
- Image gallery
- Tags for images (FancyBox), wide images, tabbed code blocks, highlighted text, alerts
- Table of contents  
  
**Integrated services:**  

- Disqus
- Google analytics
- Gravatar
- Facebook Insights

### Missing features from original *Hexo* version

- [ ] Support internationalization (i18) (https://github.com/kakawait/hugo-tranquilpeak-theme/issues/9)
- [ ] Duoshuo
- [ ] Baidu analytics
- [ ] Algolia (https://github.com/kakawait/hugo-tranquilpeak-theme/issues/8)
- [ ] Pagination custumization `tag_pagination`, `category_pagination` and `archive_pagination` (https://github.com/kakawait/hugo-tranquilpeak-theme/issues/17)

**ATTENTION** following features will not be possible due to *Hugo* limitations

- Archives pages by years `/archives/2015`
- Archives pages by month `/archives/2015/01`

## Quick start

**Please read [user documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md), it's short and useful to discover all features and possibilities of the theme, especially the  [writing posts](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md#writing-posts) section**

### For people who want to use the original version of Tranquilpeak without modifications (users)

Go to the directory where you have your Hugo site and run:

```shell
mkdir themes
cd themes
git clone https://github.com/kakawait/hugo-tranquilpeak-theme.git
```

After installing the Tranquilpeak theme successfully, we recommend you to take a look at the [exampleSite](exampleSite) directory. You will find a working Hugo site configured with the Universal theme that you can use as a starting point for your site.

First, let's take a look at the [config.toml](exampleSite/config.tom). It will be useful to learn how to customize your site. Feel free to play around with the settings.

More information on [user documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md) to install and configure the theme  

### For people who want to create their own version of tranquilpeak (developers) 

1. Run `git clone https://github.com/kakawait/hugo-tranquilpeak-theme.git`  
2. Follow [developer documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/developer.md) to edit and build the theme 

## Demo

Check out Tranquilpeak theme in live : [hugo-tranquilpeak-theme demo](https://tranquilpeak.kakawait.com)

## Showcase

Checkout showcase https://github.com/kakawait/hugo-tranquilpeak-theme/wiki/Showcase

### How can I add my site to the showcase
  
**Click [here](https://github.com/kakawait/hugo-tranquilpeak-theme/issues/new?title=Add%20my%20blog%20into%20the%20showcase&body=Hey,%20add%20my%20blog%20into%20the%20showcase:) to add your blog into the showcase.**

Please fill the following information:

1. public url
2. name (optional)
3. description (optional)

## Documentation

If it's your first time using Hugo, please check [Hugo official documentation](https://gohugo.io/overview/introduction/)

### For users  

To install and configure the theme, consult the following documentation : [user documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md)  

### For developers

To understand the code, the workflow and edit the theme, consult the following documentation : [developer documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/developer.md)

## Contributing

All kinds of contributions (enhancements, new features, documentation & code improvements, issues & bugs reporting) are welcome.

As explained on [Credits](#credits):

> *Hugo* version keeps every `.js` and `.css` files untouched from original *Hexo* version in order to enjoy futur original *Hexo* version updates or features! 

That mean I would keep a stronge dependency with original *Hexo* theme. Thus if you want to suggest any modifications on `.css` or `.js` files **I will submit those changes to original *Hexo* theme** (except if it's really specific to *Hugo* bugs that is not present on *Hexo*).

## License

hugo-tranquilpeak-theme is released under the terms of the [GNU General Public License v3.0](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/LICENSE).


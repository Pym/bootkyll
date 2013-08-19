# Bootkyll

[Bootkyll](https://github.com/Pym/bootkyll) is a light them for Jekyll, made easily customizable thanks to [Bootswatch](http://bootswatch.com/).

Featuring an HTML 5 layout with Gravatar support, multiple authors, Google Analytics, Disqus and Twitter integration.

And also a nice and clean Atom support!

Crafted with love by [@Pym](https://github.com/Pym).

## Demo

You can see the theme running [on my blog](http://pym.me/).

## Requirements

This theme require [Bower](http://bower.io/), which is used to download Bootswatch.

## Installation

Clone this repository and then execute `$ bower install`.

## Default Configuration

    name: Bootkyll
    short_description: A light theme for Jekyll
    meta_description: 'Bootkyll is a light theme for Jekyll, made easily customizable with Bootswatch. Crafted with love by Pym.'
    url: http://www.bootkyll.com
    feed_url: http://feed.bootkyll.com
    theme: superhero # choose one between: amelia, cosmo, flatly, readable, slate, superhero, cerulean, cyborg, journal, simplex, spacelab, united
    image_border_color: '#E36B23' # @orange from superhero theme
    contact_email: email@domain.com
    authors:
      admin:
        display_name: Admin
        gravatar_md5: # generate md5 like this: `$ echo -n "email@domain.com" | openssl md5`
    analytics:
      enabled: false
      id:
      url:
    disqus:
      enabled: false
      shortname:
    twitter:
      enabled: true
      lang: en
      username: Pym
      hashtags: [bootkyll, jekyll]

## Note

Defaults favicons are from [HTML5 Boilerplate](http://html5boilerplate.com/).

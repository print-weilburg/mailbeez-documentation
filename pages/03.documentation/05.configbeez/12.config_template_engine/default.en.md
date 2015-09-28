---
# http://learn.getgrav.org/content/headers
title: Template Engine
slug: config_template_engine
# menu: MailBeez Analytics
date: 26-03-2012
published: true
publish_date: 26-03-2012
# unpublish_date: 26-03-2012
template: docs
# theme: false
visible: true
summary:
    enabled: true
    format: short
    size: 128
taxonomy:
    migration_status: done
    category: [docs]
    tag: [core]
# added collection selector

author:
    name: admin
metadata:
    author: admin
#      description: Your page description goes here
#      keywords: HTML, CSS, XML, JavaScript
#      robots: noindex, nofollow
#      og:
#          title: The Rock
#          type: video.movie
#          url: http://www.imdb.com/title/tt0117500/
#          image: http://ia.media-imdb.com/images/rock.jpg
#  cache_enable: false
#  last_modified: true
---

MailBeez utilizes the popular template system "[Smarty](http://smarty.net)" to generate email content.

Here you can empty the cache of the template system.

No all email clients support external CSS files, so by default all CSS are converted into inline CSS. In case this causes issues with custom templates you can deactivate this behaviour.
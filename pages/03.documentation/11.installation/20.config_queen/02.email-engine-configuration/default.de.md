---
# http://learn.getgrav.org/content/headers
title: Email Engine Konfiguration
slug: email-engine-configuration
# menu: Email Engine Konfiguration
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
    migration-status: review
    category: [docs]
    tag: []
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

(English) Requires MailBeez V2.6

With MailBeez V2.6 you are able to choose if you would like to use the Email-Engine of the underlying store system or MailBeez own email engine.

Pro:  
 - enables bounce handling (requires addtional configuration)  
 - full control on email content and layout  
 - DKIM Support (PHP5)  
 - option to send only in TXT format

Cons:  
 - additional configuration efforts

Gmail:  
 smtp.gmail.com  
 Auth: true  
 security: ssl  
 Port: 465

---
# http://learn.getgrav.org/content/headers
title: Winback Advanced Cross Check
slug: filter_check_winback_advanced
# menu: Winback Advanced Cross Check
date: 16-10-2012
published: true
publish_date: 16-10-2012
# unpublish_date: 16-10-2012
# template: false
# theme: false
visible: true
summary:
    enabled: true
    format: short
    size: 128
taxonomy:
    migration-status: review
    category: []
    tag: []
# added collection selector

author:
    name: kelly
metadata:
    author: kelly
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

## Don’t Duplicate Your Emails

Delivered with the [Winback Advanced](http://www.mailbeez.com/documentation/mailbeez/winback_advanced/) module, this filter checks for customers who have blocked or already received Winback emails from the Winback Simple module before sending out emails when the Winback Advanced module is run.

If you were running the Simple version of the module prior to installing the Advanced version, this filter ensures that customers won’t receive the same email twice (once from each version), or at all if they have opted-out.

If you begin using the Winback Advanced module without ever having run the Winback Simple module, then there is no need to enable this filter.

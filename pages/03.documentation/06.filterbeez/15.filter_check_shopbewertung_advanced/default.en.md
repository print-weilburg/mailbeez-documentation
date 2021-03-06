---
# http://learn.getgrav.org/content/headers
title: Shopbewertung Advanced Cross Check
slug: filter_check_shopbewertung_advanced
# menu: Shopbewertung Advanced Cross Check
date: 18-12-2012
published: true
publish_date: 18-12-2012
# unpublish_date: 18-12-2012
template: docs
# theme: false
visible: true
summary:
    enabled: true
    format: short
    size: 128
taxonomy:
    migration_status: review
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

Delivered with the [Shopbewertung Advanced](/documentation/mailbeez/shopbewertung_advanced/) module, this filter checks for customers who have blocked or already received Shopbewertung emails from the Shopbewertung Simple module before sending out emails when the Shopbewertung Advanced module is run.

If you were running the Shopbewertung version of the module prior to installing the Advanced version, this filter ensures that customers won’t receive the same email twice (once from each version), or at all if they have opted-out.

If you begin using the Shopbewertung Advanced module without ever having run the Shopbewertung Simple module, then there is no need to enable this filter.

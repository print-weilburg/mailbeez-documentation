---
# http://learn.getgrav.org/content/headers
title: Share Review on Facebook
slug: review_facebook
# menu: Share Review on Facebook
date: 04-06-2010
published: true
publish_date: 04-06-2010
# unpublish_date: 04-06-2010
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
download:
    category: [mailbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2010/06/facebook_112.png'
    pro: ''
    cert: ''
    price: ''
    title_en: 'Share Review on Facebook'
    teaser_en: ''
    title_de: 'Bewertung auf Facebook teilen'
    teaser_de: 'Bitte Kunden, ihre Produktbewertung auf Facebook zu teilen'
    author: 'MailBeez.com'
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

This Module will offer your customers to share their reviews on Facebook.

![](http://www.mailbeez.com/wp-content/uploads/2010/06/facebook.png "facebook")The email contains a list of purchased products with

- Image
- direct link to Facebook sharerer

Like all MailBeez Moduls the email content is taken from a template, the list of products is defined in a sub-template.

The Facebook Sharer link is pointing to the review-info page where the review defined by products\_id and review\_id is displayed. Facebook is able to extract the Review-Text from this page.

**Changelog**

v1.1  
 Bugfix:  
 - added rewrite of img url to add absolute server path

V1.0  
 initial version
v1.1 
Bugfix:
- added rewrite of img url to add absolute server path


v1.2 
optimization:
- added early check in getAudience to avoid execution when no email to send


v1.3
- $storename, $storeurl now global (mailbeez v1.3)
- corrected replacement of testList in send testemail

v1.4
- corrected path-information for zencart


v1.5
- removed platform incompatibility



v2.0
- new templates
- check for approval if exists
- compatible with "early check" setting

v2.2
- move images into module folder

V2.3
- compatibility with MailBeez V2.6

V2.4
- bugfixes

V2.5
- compatibility with Gambio
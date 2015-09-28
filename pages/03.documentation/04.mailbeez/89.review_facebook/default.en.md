---
# http://learn.getgrav.org/content/headers
title: Share Review on Facebook
slug: review_facebook
# menu: Share Review on Facebook
date: 04-06-2010
published: true
publish_date: 04-06-2010
# unpublish_date: 04-06-2010
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
    tag: [ce]
module:
    code: 'review_facebook'
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

The email contains a list of purchased products with

- Image
- direct link to Facebook sharerer

Like all MailBeez Moduls the email content is taken from a template, the list of products is defined in a sub-template.

The Facebook Sharer link is pointing to the review-info page where the review defined by products_id and review_id is displayed. 
Facebook should be able to extract the Review-Text from this page.

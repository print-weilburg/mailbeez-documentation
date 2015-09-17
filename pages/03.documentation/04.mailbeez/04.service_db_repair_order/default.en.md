---
# http://learn.getgrav.org/content/headers
title: Service-Module: Repair Orders DB
slug: service_db_repair_order
# menu: Service-Module: Repair Orders DB
date: 07-02-2013
published: true
publish_date: 07-02-2013
# unpublish_date: 07-02-2013
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
download:
    code: 'service_db_repair_order'
    category: [mailbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: ''
    pro: 'pro'
    cert: 'true'
    price: '29 EUR'
    title_en: 'Service-Module: Repair Orders DB '
    teaser_en: 'This module repairs corrupted Order Databases'
    title_de: 'Service-Modul: Repariere Bestell-Datenbank'
    teaser_de: 'Dieses Modul repariert korrupte Bestell-Datenbanken'
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

## Problem:

External order management solutions or custom addons can cause corrupted Order Database Tables.

## Symptom:

The Order status in the order overview does not match with the Order Status in the Order-Edit View.  
 MailBeez modules can’t find any or not all orders / customers.

## Solution:

This module automatically repairs the corrupted Order Database Tables

Features:

- In Simulation mode only the corrupted Orders are listed, but not repaired
- runs very efficiently before all other modules
- You can choose, if you want to keep the Order Status or assign a new order status to repaired orders
Version 2.1:
- initial public release
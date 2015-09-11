---
# http://learn.getgrav.org/content/headers
title: Run MailBeez automatically - Advanced
slug: config_cron_advanced
# menu: Run MailBeez automatically - Advanced
date: 02-12-2013
published: true
publish_date: 02-12-2013
# unpublish_date: 02-12-2013
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
download:
    code: 'config_cron_advanced'
    category: [configbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2013/12/icon_cron_64.png'
    pro: 'pro'
    cert: 'true'
    price: '99 EUR'
    title_en: 'Run MailBeez Automatically Advanced'
    teaser_en: 'Add automation and powerful time control - also great in combination with traditional cronjobs'
    title_de: 'MailBeez automatisch ausführen - Profi'
    teaser_de: 'Automatisierung und volle Zeitkontrolle - auch gerade in Kombination mit traditionellen Cronjobs'
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

This module allows you to define the timing for running modules. Compared to the "Run MailBeez automatically" Module it adds the powerful time control.

**Benefits**

- control per module at which week days and at which time to send out.   
E.g. sent Welcome Emails with providing quick support only during your business hours
- reduce load for the sending process.  
Depending on the server setup, number of modules installed and configuration then sending process might require too many resources. By splitting up the processing you can reduce the load.



**Set-up:**

The "Run MailBeez automatically advanced" module included the basic "Run MailBeez automatically" to utilise the traffic on the website to trigger the sending process. This happens asynchronous, which means the visitor will not see any delay in page load times.

But also when using a traditional cronjob this module gives full control about when to run which MailBeez campaign module.

You can set up the cronjob to call the MailBeez Cronjob-URL e.g. every 5 minutes and then configure very flexible and comfortable the timing for each module.
V1.1
- added localization (EN, DE) for weekday names
- improved instructions

V1.0
- initial public release
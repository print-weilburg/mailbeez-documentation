---
# http://learn.getgrav.org/content/headers
title: Welcome Email
slug: create_account
# menu: Welcome Email
date: 10-05-2011
published: true
publish_date: 10-05-2011
# unpublish_date: 10-05-2011
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
    code: 'create_account'
    category: [mailbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/05/icon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '29 EUR'
    title_en: 'Welcome Email'
    teaser_en: 'Send a welcome email to new customers'
    title_de: 'Willkommens Email'
    teaser_de: 'Sende eine Begr&uuml;ssung an neue Kunden'
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

**A helpful module that sends out a welcome email a defined period of time after a customer has created an account.**

You might be thinking that this module simply doubles up on the email that your shopping cart system already sends when a customer creates an account. However, with some creative thinking, this secondary ‘welcome’ email can be used for some really interesting ideas, like providing additional store information, or to alert the customer to current special offers. With the rise on social commerce, this email could even be exclusively tailored to attract visitors to your Facebook or Twitter pages.

**Add gender for dynamic content**

For stores that cater for both men and women, this second MailBeez generated email could actually be used for more advanced email processes, like providing differentiated content for male and female recipients, which would make use of the Mailbeez “[Add Gender](http://www.mailbeez.com/documentation/filterbeez/filter_add_gender/ "Add Gender")” plugin.

**Easy configuration**

The options for this module include the following parameters, which should look quite familiar and straight forward:

- **Set days delay after create account** The number of days delay after the creation of a new account before sending the emails
- **Set days to skip after** The number of days after which to skip the create account email (in case cron job failed)
- **Sender email** The sender’s email
- **Sender name** The sender’s name
- **Sort order of display**. Sort order of display. Lowest is displayed first.

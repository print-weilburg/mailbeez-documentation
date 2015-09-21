---
# http://learn.getgrav.org/content/headers
title: Newsletter Advanced
slug: newsletter
routes:
    aliases:
        - /documentation/mailbeez/mb_newsletter
# menu: Newsletter Advanced
date: 11-08-2011
published: true
publish_date: 11-08-2011
# unpublish_date: 11-08-2011
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
    tag: [pro,coupon]
module:
    code: 'mb_newsletter'
    category: [mailbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/10/icon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '179 EUR'
    title_en: 'Newsletter Advanced'
    teaser_en: 'The Newsletter Module for MailBeez, with Segmentation, Coupons and more'
    title_de: 'Newsletter Profi'
    teaser_de: 'Das Newsletter Module für MailBeez, mit Segmentierung, Gutscheinen und mehr'
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

The Mailbeez Newsletter module represents a completely new approach to an integrated eCommerce newsletter module, offering store owners exciting Mailbeez enhancements, and the ability to create personalized, intelligent email campaigns right from the store admin area.

**Responsive Newsletter**  
In combination with the Responsive Template Manager the Newsletter will get the ability to design and send responsive Emails, read more about [Responsive Emails with MailBeez](/documentation/responsive-emails/)

Sending an email newsletter from a vanilla install of any OScommerce variant system is a very unappetizing task, which is why there has, in recent years, been a proliferation of 3rd party email newsletter subscribers who have provided the tools most merchants wished their eCommerce store could provide. However, with the introduction of the Mailbeez Newsletter module, store owners finally have the tools to create email campaigns from their admin areas; campaigns that lack nothing in comparison to the offerings of feature rich 3rd party systems.

As a seamless integrated module the MailBeez Newsletter Advanced Module has direct access to customers and their newsletter subscription setting. That allows your to e.g. send a newsletter campaign to all your subscribed customers without exporting or importing any data!

The process of creating and editing newsletter is very easy: the intuitive visual editor allows you to create professional newsletters, which will show up best possible across different email clients. In combination with the [Responsive Template Manager](/documentation/mailbeez/config_tmplmngr/) (part of [MailBeez Essentials Pack](http://www.mailbeez.com/download/mailbeez-essential-pack/)) you will also be able to create mobil-friendly responsive newsletters which will look great e.g. on your customers iPhone.



### Examples:

The powerful segmentation rules allow you to create a virtually endless number of targeted newsletter campaigns:

**Last year's 1-time holiday shoppers**

- segmentation: 1 purchase between 1st of october 2012 and 31st of december 2012
- coupon: 10% off, valid for 14 days
- 

**season newsletters to all customers**

- pre-program your season newsletters
- no segementation

**welcome newsletter series**

- segmentation: customer since x days, but less than y day

**product recall / warning email**

- segmentation: customers, who purchased product x, regardless of their newsletter subscription status

**Upsell / Cross-Sell**

- segmentation: customers, who purchased product x, but not product y
- coupon: free shipping within 7 days.

### Features

**lists**

- create, edit and delete lists for recipients
- unlimited number of lists
- segmentation of lists
- test of segmentation

**Segmentation features**

- geographic: country, state, zip-code
- customer: gender, customer since min/max days, customer groups: requires [Customer Group-Filter](/documentation/mailbeez/filter_check_group/)
- products: purchased / must not have purchased (whitelist/blacklist)
- categories: purchased / must not have purchased (whitelist/blacklist)
- orders: max. number of orders, last order before / after date
- configure countries to ignore customer subscription status for

**campaigns**

- create, edit and delete campaigns
- unlimited number of campaigns
- a campaign can hold unlimited number of newsletters
- assign default list for campaigns (can be overridden on newsletter level)

**Newsletter**

- active from / to date
- select list or you campaign default
- select coupon template

**Coupons**

- utilising the MailBeez coupon engine
- create coupon templates utilising all available options
- automatically generated personalised coupons
- configure the length and number of days being valid

**reports**

- fully integrated with MailBeez Analytics and Google Analytics
- analyse open, click, order

### sending process

Newsletter can be sent either manually or automatically. With each run the sending process will send the number of emails you configured as "chunk size". So you need to run the sending process often enough until the complete list has been sent out.

**Configuration example for automata sending:**

Set up a cronjob (e.g. all 5 minutes), which exclusively will work on the newsletter modules::

 
    wget -O - -q -t 1 <cronurl>\&module=mb_newsletter


chunk size:

 
    100 Emails


Simple throttling (additional module):

 
    3600 Emails per hour


Per run the sending process will send out 100 Emails, approx. 1 per Second. The Cronjob starts the sending process every 5 minutes (12 times per hour), so it will send out 1200 Emails per hours.

Depending on your mailserver you can increase the throughput or you need to increase it.

Thanks to throttling and limiting the number of emails sent per run (chunk size) you can stay within the limits given by your hoster or email server. Also this helps to reduce the risk of getting a spam rating.

### recommendes modules

For best operations we recommend following modules, which will enhance the MailBeez platform. So all other MailBeez modules will be enhanced.

- [Simple Throttling](/documentation/mailbeez/filter_do_throttling_simple) (part of [MailBeez Essentials Pack](http://www.mailbeez.com/download/mailbeez-essential-pack/))
- [BounceHive Bounce Handling](/documentation/mailbeez/config_bouncehive_advanced)
- [Customer Group-Filter](/documentation/mailbeez/filter_check_group/)

To create and send responsive Emails you need to install the Responsive Template Manager:

- [Responsive Template Manager](/documentation/mailbeez/config_tmplmngr/) (part of [MailBeez Essentials Pack](http://www.mailbeez.com/download/mailbeez-essential-pack/))

### future developments

- additional Email-templates
- additional content templates
- Insert MailBeez Template-Tags with buttons (currently only firstname & lastname)
- automatically create product content blocks
- personalised contents
- Support for "prospect": Visitors can sign-up for the newsletter. Once they convert into a customer the system will recognise it. That allows to sent different newsletters to prospects and customers.

## have some ideas?

![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/icons/slategrey/Megaphone.png) Tell them! MailBeez is developed for merchants so your ideas, feedback and input is very important!

[ My idea for the newsletter module](http://helpdesk.mailbeez.com/509106-MailBeez)
V2.32
- fixed bug in segmentation engine

V2.31
- fixed bug in segmentation engine

V2.3
- fixed bug in segmentation engine
- added "min order count" as rule

V2.26
- fixed bug in segmentation engine

V2.25
- fixed an issue with prospects management

V2.2
- improved segmentation engine
- added categories filter
- improved products filter (blacklist now across orders)

V2.1
- added zipcode filter
- added support for customer profiling engine

V2.0
- added extendable segmentation engine

V1.4
- added support for modified-shop 1.06 / newsletter_recipients table

V1.3
- fixed issue with groupfilter
- improve responsive button (outlook)

V1.2
- minor fixes

V1.1
- minor changes

V1.0
- initial public release
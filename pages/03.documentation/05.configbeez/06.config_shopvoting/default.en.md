---
# http://learn.getgrav.org/content/headers
title: Shopvoting
slug: config_shopvoting
# menu: Shopvoting
date: 01-04-2014
published: true
publish_date: 01-04-2014
# unpublish_date: 01-04-2014
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
    tag: [core]
module:
    code: 'config_shopvoting'
    category: [configbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2014/06/icon_32.png'
    pro: ''
    cert: ''
    price: 'FREE'
    title_en: 'Shop Voting'
    teaser_en: 'Allow your customers to vote your store and utilize the results to increase conversion'
    title_de: 'Shopbewertungen'
    teaser_de: 'Geben Sie Ihren Kunden die Möglichkeit Ihren Shop zu bewerten und nutzen Sie die Ergebnisse zur Konversion-Optimierung'
    author: 'Web4design.de'
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

this module is developed by [www.web4design.de](http://www.web4design.de/) in close cooperation with MailBeez.

 [Go to manual](http://www.web4design.de/module_infos/english/shopreviews/index.php) Plays well together with [Shopvoting Invitation Advanced](/documentation/mailbeez/shoprating_advanced/) module with auto-login, frequent-buyer recognition and more pro features

## customers reviews - self hosted

This add-on allows your customer to vote your stores and give a review.

With a nicely designed widget you can display the reviews in your shopping cart.

The design and layout is comparable to hosted solutions, but you have full control on your ratings - and all for free.

The module hooks into the [BeezDesk CRM Customer Insight](/documentation/configbeez/config_customer_insight/) so you will the notifications for new shopvotings. Also you are able to see shop voting for the customer you currently work on.

**following screenshots of the module:**

![image](http://www.web4design.de/module_infos/english/shopreviews/img/infosfunctions.jpg)

## More Information

### Looks great and improves conversion

![](http://www.mailbeez.com/images/en_shoprating_box.png)

The new MailBeez Shopvoting Module allows your customers to rate your store and service. Hosted on your own server with complete control.

**Store-Ratings are known to increase conversion and for this good reason there are many online services for hosted Store-Ratings.**

However not everyone likes the idea of not having control on the ratings, sharing customer data and getting locked into a monthly fee. That’s why we teamed up with **[www.web4design.de](http://www.web4design.de/)**, who has developed a beautiful and great working for self-hosted store ratings already helping 1000's of online stores to increase conversion.

 [visit Module page](/documentation/configbeez/config_shopvoting/) **Store ratings or product reviews? Both!**   
Store ratings and [product reviews](/documentation/mailbeez/review_advanced/) are complementary, so you can use them both in your store.

We recommend to ask your customers for a store rating short after delivery and e.g. 30 days later for a review of their purchased products. **Two natural points of contact** which improve your **customer interaction** and **brand recognition** - and will increase your revenue!

### Easy drop-in installation

The core-module can be installed into MailBeez by dropping in the new files. You only need to insert the code-snippet for displaying the badge into your store-front.

### Professional Rating-Page included

Clicking on the badge opens a professional designed page showing details about the ratings and allowing customers to place a new rating as well (better invite them using MailBeez ;) ).

[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.com/images/en_shoprating_page.png&w=600&h=500&zc=1&q=100 "rating page")](http://www.mailbeez.com/images/en_shoprating_page.png "rating page")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)

### Get serious - go advanced

While the free module already works great, professional stores will go for the MailBeez Premium add-on "[Shopvoting Invitation Advanced](/documentation/mailbeez/shoprating_advanced/)" which provides a range of advanced features like **auto-login** and **recognition of regular customers** which will generate up to twice as many ratings. And you can even **integrate real-time ratings in any MailBeez-generated Email** by placing a simple template tag

 [go to Pro-Module](/documentation/mailbeez/shoprating_advanced/) Shopratings in MailBeez Emails

[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.com/images/en_shoprating_advanced_integration.png&w=250&h=350&zc=1&q=100 "Shopratings in MailBeez Emails")](http://www.mailbeez.com/images/en_shoprating_advanced_integration.png "Shopratings in MailBeez Emails")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)

### Integrated into free BeezDesk CRM Customer Insight

[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.com/images/en_shoprating_notification.png&w=600&h=400&zc=1&q=100 "notifications")](http://www.mailbeez.com/images/en_shoprating_notification.png "notifications")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)

Just install the free [BeezDesk CRM Customer Insight](/documentation/configbeez/config_customer_insight/) and integrate it into your Store Admin panel by adding a single code-line and you will get **notified about new customer ratings**, see the current rating summary and have **direct access to the configuration panel** of the MailBeez Shopvoting Module!

Great! and free!

 [get free BeezDesk CRM Customer Insight](/documentation/configbeez/config_customer_insight/)
V3.33
- insert a missing language constant "RECEIVED_SHOPREVIEW"

V3.32
- fixed an admin url bug (orders link)

V3.31
- fixed typo excelent -> excellent
- activated automatic install to avoid installation issue

V3.30
- new feature - now it is possible to change the firstname and lastname of the review writer at the admin panel
- fixed html-form bug on shop-review_write.html - !!Important!! to update
- improved the gambio plugin to avoid errors before the module is installed

V3.29
- fixed prefix-bug in Shopvoting.php to solve problems with ZenCart

V3.28
- change some .classes to #id to prevent overriding css
- fixed some html bugs

V3.27
- change class loading (autloader function)
- hide the backlink in the shopreview-box (it is only hidden, not removed)
- fix some HTML Bugs
- change all box-templates
- additional css classes

V3.26
- fixed SSL Bug
- installation guide gambio updated

V3.25
- added plugin for Gambio

V3.2
- Bugfixes
- integrated mailbeez/shoprating email module

V3.1
- BeezDesk Customer Insight Plugin
- support for osCommerce 2.2 and 2.3+
- support for ZenCart
- pre-integration for shoprating advanced module

V3.0
- first public version

V3.0 Beta
- first beta version
---
# http://learn.getgrav.org/content/headers
title: Notification: Order Status Update
slug: notification_order_status
# menu: Notification: Order Status Update
date: 01-03-2013
published: true
publish_date: 01-03-2013
# unpublish_date: 01-03-2013
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
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2013/03/icon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '49 EUR'
    title_en: 'Notification: Order Status Update'
    teaser_en: 'Notify your customers about an specific order status update, e.g. to send a delivery tracking link'
    title_de: 'Benachrichtigung: Bestell-Status Änderung'
    teaser_de: 'Benachrichtigen Sie Ihre Kunden bei speziellen Bestell-Status Änderungen, z.B. um einen Link zur Paket-Verfolgung zu schicken'
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

This handy module sends a custom notification email to the customer once an order is set to one ore more configured order status.

Optionally you can configure the module to change the order status to a new status. The order comment, order status name and order status date can be inserted into the email using a template variable.

The notification email is sent the next time MailBeez sends out emails - it is recommended to set up a cronjob running every minute to reduce the time delay between setting the order status and sending out the notification email. The MailBeez Support is happy to help you in case you have some questions.

Scenarios where this module can be applied:

- an external order management solution updates the order status, but does not sent any notification email
- you would like to replace the default order status update email with a custom designed email
- you would like to automatise processes depending on the order status

**template variables**

 Template VariableOutput{$status\_date}formated order status date{$status\_date\_raw}  
{$ORDER\_STATUS\_DATE}raw order status date{$status\_id}status id{$status\_name}  
{$ORDER\_STATUS}order status name{$comments}comments
V2.3
- added order status name as template variable

V2.2
- added configuration for sender and sender name

V2.1
- supporting multiple notifications per order (for each status one)

V2.0
- initial public version

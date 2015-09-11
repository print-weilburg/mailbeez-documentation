---
# http://learn.getgrav.org/content/headers
title: Coupon: Send Reorder Coupon
slug: coupon_reorder
# menu: Coupon: Send Reorder Coupon
date: 03-09-2010
published: true
publish_date: 03-09-2010
# unpublish_date: 03-09-2010
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

(English) DISCONTINUED – Please use [Reorder Advanced](http://www.mailbeez.com/documentation/mailbeez/reorder_advanced/)

This Coupon-Reorder MailBeez Module does track to which customer the coupon was send – this allows to send later a coupon-expiry reminder (“only 5 days left to use your coupon”) – that’s how it should be ![;-)](http://localhost/wordpress_mailbeez_EOL/wp-includes/images/smilies/icon_wink.gif)

This module sends a reorder coupon to customers in a given timeframe after an order.

Like all MailBeez Moduls the email content is taken from a template, the list of products is defined in a sub-template.

The default template for the content looks like this and is very easy to customize:

    [html]<br></br>
    <img src="$catalog_servermailhive/mailbeez/coupon_campaign/images/coupon.png" border="0" hspace="0" vspace="0" width="128" height="128" align="right" ><br></br>
    <!-- image found on http://findicons.com/icon/251134/gift might be protected by copyrights --><br></br>
    <br><br></br>
    Dear $firstname $lastname,<br><br></br>
    <br><br></br>
    thank you very much again for your order at $storename.<br></br>
    <br><br></br>
    We would be happy to welcome you again at our store and would like to give you a coupon for your next order:<br><br></br>
    <br><br></br>
    <blockquote style="border: 1px dotted gray; padding: 10px;"><br></br>
    <b>$coupon_name</b><br><br></br>
    <b>Coupon-Code: $coupon_code</b><br><br></br>
    Amount: $coupon_amount<br><br></br>
    minium order amount: $coupon_minimum_order<br><br></br>
    Valid until: $coupon_expire_date<br><br></br>
    </blockquote>

<br>

sincerly yours,  
 <blockquote>$storename</blockquote>

<br>  
 <br>  
 your email: $email\_address[/html]

the email-master template is also defined in a text-file and can be easily customized as well

[![](http://www.mailbeez.com/wp-content/uploads/2010/10/mail_coupon_reorder-243x300.png "mail_coupon_reorder")](http://www.mailbeez.com/wp-content/uploads/2010/10/mail_coupon_reorder.png)Default Template

 

Configuration:

**Set Order Status**  
 Set the status of orders to send a coupon

**Set days passed**  
 number of days since last order

**Set days to skip after**  
 number of days after which do skip the reorder couponl

**Choose Coupon**  
 Choose the coupon code as you have configured in the coupon system

Questions? Ideas? Please [contact ](http://localhost/wordpress_mailbeez_EOL/about/contact/)me

[license\_1]

---
# http://learn.getgrav.org/content/headers
title: Review Reward Coupon
slug: coupon_review
routes:
    aliases:
        - /documentation/mailbeez/review-reward-coupon
# menu: Review Reward Coupon
date: 21-10-2011
published: true
publish_date: 21-10-2011
# unpublish_date: 21-10-2011
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
    code: 'coupon_review'
    category: [mailbeez]
    compatiblity: [comp_cre,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/10/coupon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '99 EUR'
    title_en: 'Review Reward Coupon'
    teaser_en: 'Say thanks to your customers for giving a review, and send them an automated email with a personalized coupon'
    title_de: 'Gutschein für Bewertungen'
    teaser_de: 'Bedanken Sie sich beim Kunden für das Abgeben von Produktbewertungen'
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

**Say thanks to your customers for giving a review, and send them an automated email with a personalized coupon towards their next purchase with the Mailbeez Review Reward Coupon module.**

If you are already using the [Mailbeez Review Advanced module](/documentation/mailbeez/review_advanced/ "Mailbeez Review Advanced Module") to collect more product reviews for your store, then the new Review Reward Coupon module is a powerful way to augment the review cycle by rewarding customers with a personalized offer coupon email after they have written a review. Fully automated and personalized (for that is the Mailbeez way!), the module offers powerful functionality to send the coupon after a preset number of reviews have been written, and of course, to alter the value of the coupon or deal you wish to offer the reviewer.

**Personalized coupons to prevent code sharing **

Providing standard coupon codes is a broad sword approach which can leave you open to an unwanted viral effect if your coupon gets posted around the internet. To neatly avoid this pitfall, Mailbeez automatically creates personalized coupons for each customer in your campaign, making it impossible for other customers to use the same code and benefit from the offer.

 

**Professional templates**  
 choose with a mouse click from a list of professional templates, which are easy to adjust:

**Want responsive Emails with MailBeez?**  
![](http://www.mailbeez.com/images/responsive.png) ([what are responsive emails?](/documentation/responsive-emails/)) In combination with the [responsive template manager](/documentation/mailbeez/config_tmplmngr) you are able to select a responsive email template for this module and adopt it to your design.   
The shown themed email templates are not yet responsive, we plan to make that as soon as possible (support for responsive emails will require in any case the [responsive template manager](/documentation/mailbeez/config_tmplmngr)). ****


## **Installed in seconds**  
  


As with all Mailbeez modules, installation is as simple as copying a few files into your FTP. However, as this module uses coupon functionality, please note the instructions below in order to sync your store’s coupon codes with Mailbeez.

**Step 1: Setting up coupons for use in Mailbeez**

In order to see a list of defined coupons within Mailbeez, you first have to go to your store’s coupon admin area and set up individual coupon templates for each campaign you would like to run.

**Please follow the simple steps below to get started:**

- **Coupon code field **- Use the naming convention, ‘template\_review\_reward’ in this entry field, not a coupon code, as Mailbeez will create the coupon codes automatically and individually for each email you send.
- **Coupon name field** – Enter the name of the coupon for easy retrieval later, for example ‘Review Reward’
- **Coupon dates** – Please ignore these fields, as Mailbeez will override these settings in configuring the expiration date for your campaign
- **Uses per coupon** – Set this to ’1′

**Step 2: Set up the MailBeez Modules**

Once the coupon templates are set up, go back to the MailBeez Module area within your store’s admin and assign the prepared coupon templates to your Mailbeez module, which in this case is the Review Reward Coupon plugin, by choosing them from the drop-down list to the right hand side.

Once the coupon template(s) are assigned to the Review Reward Coupon module, set MailBeez into “Simulation”-Mode and run the module. When you are happy with the results, put MailBeez back to Production mode.

**NOTE** – During simulation testing, individually generated coupons will be marked with [SIM] to make them easy to distinguish and delete from your coupon area after testing with the built-in function.

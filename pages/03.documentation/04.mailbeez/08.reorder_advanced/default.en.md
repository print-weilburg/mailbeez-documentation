---
# http://learn.getgrav.org/content/headers
title: Reorder Advanced
slug: reorder_advanced
routes:
    aliases:
        - /documentation/mailbeez/coupon_reorder
        - /documentation/mailbeez/reorder-advanced-with-coupons
# menu: Reorder Advanced with Coupons
date: 15-08-2011
published: true
publish_date: 15-08-2011
# unpublish_date: 15-08-2011
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
    code: 'reorder_advanced'
    category: [mailbeez]
    compatiblity: [comp_cre,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/10/coupon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '99 EUR'
    title_en: 'Reorder Advanced'
    teaser_en: 'Say thanks to your customers, and send them a reorder coupon towards their next purchase'
    title_de: 'Gutschein für die nächste Bestellung'
    teaser_de: 'Bedanken Sie sich beim Kunden für den Einkauf mit einem Gutschein für die nächste Bestellung'
    author: 'MailBeez.com'# added collection selector

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

**Say thanks to your customers, and send them a reorder coupon towards their next purchase with the Mailbeez Reorder Advanced module.**

Rewarding loyal customers with occasional offers is a great way to show your appreciation for their business, especially for online stores that exist in competitive environments where every order counts. The Mailbeez Reorder module gives you the tools to not only contact these customers a pre determined time after their initial order, but also allows you to set whether the offer is sent after their first, second, or even third order; which avoids providing the discount too early and unnecessarily hurting your margins.

**Using the 80/20 Rule to increase sales**

It’s a well known business fact that 80% of your business will come from just 20% of your customer base. In reality, this means that there will only ever be certain bedrock customers that you can rely on to drive your business forward, and neglecting these key buyers could lead to an exponential drop in revenue and sales. For this all important group, Reorder Advanced is ideally suited, and can be configured to reward regular buyers for their loyalty – not customers who place one order and never return.

**Personalized coupons to prevent code sharing **

Providing standard coupon codes is a broad sword approach which can leave you open to an unwanted viral effect as your coupon gets posted around the internet. To neatly avoid this pitfall, Mailbeez automatically creates personalized coupons for each customer in your campaign, making it impossible for other customers to use the same code and benefit from the offer.

**Intelligent activation**

Sending an offer out to a customer who’s last order is still not despatched would not be a great idea. To avoid this situation, the Reorder Advanced can be quickly configured to fire off the email campaign only to orders that match a certain order status rule; like ‘despatched’ for example.

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

- **Coupon code field **- Use the naming convention, ‘template\_reorder’ in this entry field, not a coupon code, as Mailbeez will create the coupon codes automatically and individually for each email you send.
- **Coupon name field** – Enter the name of the coupon for easy retrieval later, for example ‘Reorder’
- **Coupon dates** – Please ignore these fields, as Mailbeez will override these settings in configuring the expiration date for your campaign
- **Uses per coupon** – Set this to ’1′

**Step 2: Set up the MailBeez Modules**

Once the coupon templates are set up, go back to the MailBeez Module area within your store’s admin and assign the prepared coupon templates to your Mailbeez module, which in this case is the Reorder Advanced plugin, by choosing them from the drop-down list to the right hand side.

Once the coupon template(s) are assigned to the Reorder module, set MailBeez into “Simulation”-Mode and run the module. When you are happy with the results, put MailBeez back to Production mode.

**NOTE** – During simulation testing, individually generated coupons will be marked with [SIM] to make them easy to distinguish and delete from your coupon area after testing.  
 [license\_1]

---
# http://learn.getgrav.org/content/headers
title: Add Trustpilot Ratings
slug: filter_add_trustpilot_rss
# menu: Add Trustpilot Ratings
date: 03-05-2011
published: true
publish_date: 03-05-2011
# unpublish_date: 03-05-2011
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

**Automatically add your store’s Trustpilot.com reviews into any MailBeez email campaign with the Add Trust Pilot Filter, part of the [Trustpilot Integration Suite](http://www.mailbeez.com/documentation/configbeez/config_trustpilot_rss_importer/ "Trustpilot Integration Suite"); perfect for spicing up the [Winback](http://www.mailbeez.com/documentation/mailbeez/winback_advanced/ "Winback Advanced Module") and [No Purchase](http://www.mailbeez.com/documentation/mailbeez/nopurchase/ "Mailbeez No Purchase Modules") Mailbeez modules, **

With a default installation that uses the included template, your Trustpilot ratings will appear in a Mailbeez email like this:

[![](http://www.mailbeez.com/wp-content/uploads/2011/05/default_email_template-300x289.png "default_email_template")](http://www.mailbeez.com/wp-content/uploads/2011/05/default_email_template.png)Default Template for Email Integration

 

 

### Options:

**Number of ratings**  
 Number of ratings shown in emails (number)

**Minimum Stars**  
 Show only ratings with at least this number of stars (3-5)

**Shuffle Ratings**  
 Do you want to shuffle the ratings (True) or show only the latest ones (False)

 

### Usage:

Install and activate this Module – you need to have your store’s Trustpilot RSS feed imported & configured.

By adding the following tags into your MailBeez templates you will be able to show a configured number of Trustpilot ratings in your MailBeez generated emails. You can place the tags wherever you want, so for example if you place them within your main template the ratings will be shown in all emails, but if you place them only in your content template, you are able control exactly in which emails the ratings will be visible:

Place this into the HTML-Version of your MailBeez template file:

> `{$content.rss.trustpilot.html}`

Place his into the TXT-Version of your MailBeez template file:

> `{$content.rss.trustpilot.txt}`

the template for displaying the ratings is taken from the RSS-Feed template files

> `rss_email_html.tpl`  
> `rss_email_txt.tpl`

located in

> `mailhive\configbeez\config_trustpilot_rss_importer\templates`

More advanced users can also directly access the data object holding the ratings in the email template – the module comes with an example how to do this.

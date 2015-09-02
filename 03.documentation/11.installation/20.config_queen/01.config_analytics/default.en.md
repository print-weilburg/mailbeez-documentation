---
# http://learn.getgrav.org/content/headers
title: MailBeez Analytics Configuration
slug: config_analytics
# menu: MailBeez Analytics Configuration
date: 26-03-2012
published: true
publish_date: 26-03-2012
# unpublish_date: 26-03-2012
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

Requires MailBeez V2.6

MailBeez Analytics allows you to track:

Opening of Emails (Html with loaded images)  
 Click on Links  
 Purchases following click on email links.

The Openrates are measured using following techniques:  
 the loading of a tracker images (pix) is logged  
 the click on a link is also counting for an opened email

the tracker images uses a high-performance call to minimize server load: each opening is logged into a log-file. With every run of MailHive the server handler is importing the log file into the MailBeez Tracking Database. Afterwards the log file is deleted.

In  
 ‘includes/application\_top.php’  
 add following code at the end for the closing ?>

// MailBeez Click and Order tracker  
 require(DIR\_FS\_CATALOG . ‘mailhive/includes/clicktracker.php’);

Note: open / clicks on copy-to emails are not counted as these emails are separate emails with a different message-id. so only open / click actions of the real recipients are counted.

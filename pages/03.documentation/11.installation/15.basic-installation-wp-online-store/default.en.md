---
# http://learn.getgrav.org/content/headers
title: WP Online Store
slug: basic-installation-wp-online-store
# menu: WP Online Store
date: 14-12-2011
published: true
publish_date: 14-12-2011
# unpublish_date: 14-12-2011
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

**[WP Online Store](http://www.wponlinestore.com/ "WP Online Store") is a great solution for Word Press users keen to integrate an online store into their websites and blogs. Based upon the popular OsCommerce framework, it is not only free, but easy to install and well supported. Mailbeez is very pleased to announce support for the WP Online Store framework, which of course opens up any Word Press site in which WP online store is installed to a whole new world of email marketing automation applications.**

The Installation of MailBeez 2.6 has been successfully tested with WordPress 3.2.1 and WP Online Store 1.2.9 running on PHP 5.2.11. The installation is straightforward and can be done in a couple of minutes by following these two simple steps:

- copy new files
- modify existing files

### Requirements

You need to be able to upload new files to your WordPress WP Online Store and modify existing ones.

> FTP access to your WordPress Installation

## Step 1 – copy new files

copy following file to your admin-directory

> /wp-content/plugins/wp-online-store/admin/mailbeez.php

copy following file and folder to your catalog-directory (where your index.php is located)

> /wp-content/plugins/wp-online-store/mailhive (folder)  
>  /wp-content/plugins/wp-online-store/mailhive.php

## Step 2 – modify existing files

### 1. Add a menu entry

located and open the file

> /wp-content/plugins/wp-online-store/admin/includes/boxes/customers.php

find

> array(
>        'code' => FILENAME_ORDERS,
>        'title' => BOX_CUSTOMERS_ORDERS,
>        'link' => tep_href_link(FILENAME_ORDERS)
>     )

add after

> // mailbeez
>     ,
>     array(
>        'code' => 'mailbeez.php',
>        'title' => 'MailBeez',
>        'link' => tep_href_link('mailbeez.php')
>     ),
>     // - mailbeez

this will add the menu-entry “MailBeez” to your Customers Menu in WP Online Store.

### 2. check WP Online Store configuration setting

check the WP Online Store configuration file located in

> /wp-content/plugins/wp-online-store/includes/configure.php

the path defined for DIR\_FS\_CATALOG must end with a / like this:

> define('DIR_FS_CATALOG','/wp-content/plugins/wp-online-store<strong>/</strong>'); // must end with a /

 

## Next Steps

Now that your MailBeez installation is complete, you are encouraged to visit our [ Guide to Getting Started](http://www.mailbeez.com/documentation/tutorials/guide-to-getting-started/) to familiarize yourself with MailBeez features and functionality, and to learn how to configure and customize your MailBeez installation to suit your needs.

No thanks, just take me to the [Quick Start Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-quick-start-configuration-tutorial/)  
 No thanks, just take me to the [Comprehensive Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-comprehensive-configuration-tutorial/)

---
# http://learn.getgrav.org/content/headers
title: Digistore 4.1
slug: digistore-2
# menu: Digistore 4.1
date: 22-09-2011
published: true
publish_date: 22-09-2011
# unpublish_date: 22-09-2011
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

The Installation of MailBeez is successfully tested with * *DigiStore 4.1, running on PHP 5.2.11

If MailBeez is not included in your DigiStore 4.1+ release please follow these instructions

The installation is straight forward and can be done in a couple of minutes by following these two steps:

- copy new files
- modify existing files

## Step 1 – copy new files

The “Quickstart Packag” Zip-File contains several folders. The Folder “catalog” contains the files and folders you need to copy into your Shop Root.

Copy following file and folder to your Shop Root (where your index.php is located)

> catalog/admin/mailbeez.php -> admin/mailbeez.php  
>  catalog/mailhive -> mailhive (folder)  
>  catalog/mailhive.php -> mailhive.php

## Step 2 – modify existing files

### 1. Add a menu entry

located and open the file

> admin/includes/boxes/email.php

find

> '<a href="' . tep_href_link(FILENAME_CONFIGURATION, 'gID=12', 'NONSSL') . '" class="menuBoxContentLink">' . BOX_CONFIGURATION_EMAIL_OPTIONS . '</a>');

replace with

> '<a href="' . tep_href_link(FILENAME_CONFIGURATION, 'gID=12', 'NONSSL') . '" class="menuBoxContentLink">' . BOX_CONFIGURATION_EMAIL_OPTIONS . '</a>'.
>     '<a href="' . tep_href_link('mailbeez.php', '', 'NONSSL') . '" class="menuBoxContentLink">Mail Beez</a>');

this will add the menu-entry “MailBeez” to your Email-Menu item.

Feel free to place this link whereever you want.

### **please continue with [Basic Configuration](http://localhost/wordpress_mailbeez_EOL/documentation/installation/config_queen/)**

## Optional

If you would like to have access to MailBeez core files & tables from other pages you need to add the following global DataBase and Filename definitions:

### Add the Database table definition

located and open the file

> admin/includes/database\_tables.php

add e.g. at the end

> define('TABLE_MAILBEEZ_TRACKING', 'mailbeez_tracking');
>     define('TABLE_MAILBEEZ_BLOCK', 'mailbeez_block');

do the same for your catalog:

> includes/database\_tables.php

add

> define('TABLE_MAILBEEZ_TRACKING', 'mailbeez_tracking');
>     define('TABLE_MAILBEEZ_BLOCK', 'mailbeez_block');

### Add the filename definition

located and open the file

> admin/includes/filenames.php

add e.g. at the end

> define('FILENAME_MAILBEEZ', 'mailbeez.php');
>     define('FILENAME_HIVE', 'mailhive.php');

do almost the same for your catalog:

> includes/filenames.php

add

> define('FILENAME_HIVE', 'mailhive.php');

## Next Steps

Now that your MailBeez installation is complete, you are encouraged to visit our [ Guide to Getting Started](/documentation/tutorials/guide-to-getting-started/) to familiarize yourself with MailBeez features and functionality, and to learn how to configure and customize your MailBeez installation to suit your needs.

No thanks, just take me to the [Quick Start Configuration tutorial](/documentation/tutorials/mailbeez-quick-start-configuration-tutorial/)  
 No thanks, just take me to the [Comprehensive Configuration tutorial](/documentation/tutorials/mailbeez-comprehensive-configuration-tutorial/)

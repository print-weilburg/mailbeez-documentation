---
# http://learn.getgrav.org/content/headers
title: Digistore bis V.4.0
slug: digistore
# menu: Digistore bis V.4.0
date: 24-08-2010
published: true
publish_date: 24-08-2010
# unpublish_date: 24-08-2010
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

The Installation of MailBeez is successfully tested with * *DigiStore 4.0, running on PHP 5.2.11

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

> admin/advanced\_menu.php

find

> stm_aix("p7i3","p0i0",[0,"    <?php echo   BOX_CONFIGURATION_EMAIL_OPTIONS?>  ","","",-1,-1,0,"configuration.php?gID=12"]);

add in a new line

> stm_aix("p7i3","p0i0",[0,"    MailBeez   ","","",-1,-1,0,"mailbeez.php"]);

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

Now that your MailBeez installation is complete, you are encouraged to visit our [ Guide to Getting Started](http://www.mailbeez.com/documentation/tutorials/guide-to-getting-started/) to familiarize yourself with MailBeez features and functionality, and to learn how to configure and customize your MailBeez installation to suit your needs.

No thanks, just take me to the [Quick Start Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-quick-start-configuration-tutorial/)  
 No thanks, just take me to the [Comprehensive Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-comprehensive-configuration-tutorial/)

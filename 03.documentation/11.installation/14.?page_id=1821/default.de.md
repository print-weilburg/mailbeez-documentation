---
# http://learn.getgrav.org/content/headers
title: (English) Basic Installation ecombase
slug: ID-1821
# menu: (English) Basic Installation ecombase
date: 18-08-2011
published: false
publish_date: 18-08-2011
# unpublish_date: 18-08-2011
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

(English) The Installation of MailBeez 2.5 is successfully tested with *ECB* 1.08, running on PHP 5.2.11

The installation is straight forward and can be done in a couple of minutes by following these steps:

- copy new files
- add permission (half automatic)
- Install MailBeez

MailBeez is maintaining it’s own tables – the shops existing table stay as they are.

## Step 1 – copy new files

copy following file to your admin-directory

> mailbeez.php

copy following file and folder to your catalog-directory (where your index.php is located)

> mailhive (folder)
> 
> mailhive.php

## Step 2 – modify existing files

### 1. Add a menu entry

located and open the file

> admin/includes/header.php

find

> BOX_RSS => array('acl' => true,
>                          'link' => array(FILENAME_CONFIGURATION, 'gID=27'),
>                          'icon' => 'icon_rss.png'),

add after

>     'MailBeez' => array('acl' => true,
>                          'link' => 'mailbeez.php',
>                          'icon' => '../../../mailhive/common/images/minibeez.png'),

this will add the menu-entry “MailBeez” to your Tools-Box. Feel free to place this link whereever you want.

## Step 3 – add permission

run

(shop)/mailhive.php

this will add the required permission for MailBeez for the primary admin account.

If necessary add admin permission for MailBeez for secondary admin accounts as well

**please continue with [Basic Configuration](http://localhost/wordpress_mailbeez_EOL/documentation/installation/config_queen/)**

## Optional

If you would like to have access to MailBeez core files & tables from other pages you need to add the following global DataBase and Filename definitions:

### Add the Database table definition

located and open the file

> includes/database\_tables.php

add

> define('TABLE_MAILBEEZ_TRACKING', 'mailbeez_tracking');define('TABLE_MAILBEEZ_BLOCK', 'mailbeez_block');

### Add the filename definition

located and open the file

> admin/includes/application\_top.php

add

> define('FILENAME_MAILBEEZ', 'mailbeez.php');define('FILENAME_HIVE', 'mailhive.php');

located and open the file

> includes/filenames.php

add

> define('FILENAME_MAILBEEZ', 'mailbeez.php');define('FILENAME_HIVE', 'mailhive.php');

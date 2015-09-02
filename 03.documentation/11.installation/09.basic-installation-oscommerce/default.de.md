---
# http://learn.getgrav.org/content/headers
title: osCommerce 2.2
slug: basic-installation-oscommerce
# menu: osCommerce 2.2
date: 21-05-2010
published: true
publish_date: 21-05-2010
# unpublish_date: 21-05-2010
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

The Installation of MailBeez is successfully tested with osCommerce ms2.2 / rca2, running on PHP 5.2.11

The installation is straight forward and can be done in a couple of minutes by following these two steps:

- copy new files
- modify existing files

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

> admin/includes/boxes/tools.php

find

> BOX_TOOLS_WHOS_ONLINE . '</a>'

add

> . '<br><a href="' . tep_href_link(FILENAME_MAILBEEZ, '', 'NONSSL') . '">MailBeez</a><br>'

this will add the menu-entry “MailBeez” to your Tools-Box.

Feel free to place this link whereever you want.

**please continue with [Basic Configuration](http://localhost/wordpress_mailbeez_EOL/documentation/installation/config_queen/)**

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

## Weitere Schritte

Nach der Grund-Installation hilft das Tutorial [Schnelleinstieg](http://www.mailbeez.de/dokumentation/tutorials/schnelleinstieg/) weiter, die Grundlagen von MailBeez zu verstehen.

Nein Danke, bitte gleich zum Tutorial [MailBeez Konfiguration einfach](http://www.mailbeez.de/dokumentation/tutorials/mailbeez-konfiguration-einfach/)  
 Nein Danke, bitte gleich zum Tutorial [MailBeez Konfiguration ausführlich](http://www.mailbeez.de/dokumentation/tutorials/mailbeez-konfiguration-ausfuehrlich/)

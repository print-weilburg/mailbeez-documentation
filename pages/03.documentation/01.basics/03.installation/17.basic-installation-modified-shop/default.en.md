---
# http://learn.getgrav.org/content/headers
title: modified-shop 1.0x
slug: basic-installation-modified-shop
# menu: modified-shop 1.0x
date: 12-09-2010
published: true
publish_date: 12-09-2010
# unpublish_date: 12-09-2010
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

The Installation of MailBeez is successfully tested with *xtc-modified / modified-shop* 1.05, running on PHP 5.2.11

The installation is straight forward and can be done in a couple of minutes by following these steps:

- copy new files
- add permission (half automatic)
- Install MailBeez

MailBeez is maintaining it’s own tables – the shops existing table stay as they are.

## Step 1 – copy new files

copy following file to your admin-directory

> mailbeez.php

copy following file and folder to your shoproot (where your index.php is located)

> mailhive (folder)
> 
> mailhive.php

## Step 2 – modify existing files

### 1. Add a menu entry

**Modified Shop up to V1.05**  
 located and open the file

> admin/includes/column\_left.php

find

> ' . BOX_IMPORT . '</a><br>';

add

> if (($_SESSION['customers_status']
>     ['customers_status_id'] == '0') && ($admin_access['module_newsletter'] == '1')) echo '<li><a href="' . xtc_href_link('mailbeez.php') . '" class="menuBoxContentLink"> -MailBeez</a></li>';

**Modified Shop V1.06+**  
 located and open the file

> admin/includes/column\_left.php

find

> //----HILFSPROGRAMME

ABOVE this line:

 
    echo ('</ul>');

insert:

> if (($_SESSION['customers_status']
>     ['customers_status_id'] == '0') && ($admin_access['module_newsletter'] == '1')) echo '<li><a href="' . xtc_href_link('mailbeez.php') . '" class="menuBoxContentLink" > -MailBeez</a></li>';

this will add the menu-entry “MailBeez” to your Tools-Box. Feel free to place this link whereever you want.

## Step 3 – add permission

run

(shop)/mailhive.php

this will add the required permission for MailBeez for the primary admin account.

If necessary add admin permission for MailBeez for secondary admin accounts as well

## Next Steps

Now that your MailBeez installation is complete, you are encouraged to visit our [ Guide to Getting Started](/documentation/tutorials/guide-to-getting-started/) to familiarize yourself with MailBeez features and functionality, and to learn how to configure and customize your MailBeez installation to suit your needs.

No thanks, just take me to the [Quick Start Configuration tutorial](/documentation/tutorials/mailbeez-quick-start-configuration-tutorial/)  
 No thanks, just take me to the [Comprehensive Configuration tutorial](/documentation/tutorials/mailbeez-comprehensive-configuration-tutorial/)

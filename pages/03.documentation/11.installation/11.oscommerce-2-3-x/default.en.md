---
# http://learn.getgrav.org/content/headers
title: osCommerce 2.3.x
slug: oscommerce-2-3-x
# menu: osCommerce 2.3.x
date: 26-01-2011
published: true
publish_date: 26-01-2011
# unpublish_date: 26-01-2011
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

The Installation of MailBeez is successfully tested with osCommerce 2.3.1, running on PHP 5.2.11

The installation is straight forward and can be done in a couple of minutes by following these two steps:

- copy new files
- add menu entry

### Requirements

If not yet done, please [download the quickstart package](http://www.mailbeez.com/quickstart/?id=1&lang=en). You need to be able to upload new files to your osCommerce Shop and modify existing ones.

> FTP access to your osCommerce Installation

## Step 1 – copy new files

copy following file to your admin-directory

> mailbeez.php

copy following file and folder to your catalog-directory (where your index.php is located)

> mailhive (folder)
> 
> mailhive.php

## Step 2 – add menu entry

depending on your version you can either use the admin plugin or manually add the menu entry:

### A. Admin Plugin

since oscommerce 2.3.3 a plugin system for adding admin entries is available. For this version please copy

> extra\_files/extras\_osc\_233x/admin/includes/boxes/customers\_mailbeez.php

into your oscommerce system:

> admin/includes/boxes/customers\_mailbeez.php

### B. Add a menu entry

located and open the file

> admin/includes/boxes/tools.php

find

> array(
>         'code' => FILENAME_WHOS_ONLINE,
>         'title' => BOX_TOOLS_WHOS_ONLINE,
>         'link' => tep_href_link(FILENAME_WHOS_ONLINE)
>     )

add

> // mailbeez
>     ,
>     array(
>         'code' => 'mailbeez.php',
>         'title' => 'MailBeez',
>         'link' => tep_href_link('mailbeez.php')
>     )
>     // - mailbeez

this will add the menu-entry “MailBeez” to your Tools-Box.

Feel free to place this link whereever you want.

Open the MailBeez System and start exploring!

 

## Next Steps

Now that your MailBeez installation is complete, you are encouraged to visit our [ Guide to Getting Started](http://www.mailbeez.com/documentation/tutorials/guide-to-getting-started/) to familiarize yourself with MailBeez features and functionality, and to learn how to configure and customize your MailBeez installation to suit your needs.

No thanks, just take me to the [Quick Start Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-quick-start-configuration-tutorial/)  
 No thanks, just take me to the [Comprehensive Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-comprehensive-configuration-tutorial/)

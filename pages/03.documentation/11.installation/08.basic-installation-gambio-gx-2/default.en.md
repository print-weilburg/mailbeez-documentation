---
# http://learn.getgrav.org/content/headers
title: Gambio GX 2
slug: basic-installation-gambio-gx-2
# menu: Gambio GX 2
date: 15-06-2011
published: true
publish_date: 15-06-2011
# unpublish_date: 15-06-2011
template: docs
# theme: false
visible: true
summary:
    enabled: true
    format: short
    size: 128
taxonomy:
    migration-status: review
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

The Installation of MailBeez is successfully tested with *Gambio GX 2*

The installation is straight forward and can be done in a couple of minutes by following these steps:

- transfer new files
- add permission (half automatic)
- Install MailBeez

MailBeez is maintaining it's own tables - the shops existing table stay as they are.

## Step 1 - copy new files

copy following file to your admin-directory

> catalog/admin/mailbeez.php

copy following file and folder to your catalog-directory (where your index.php is located)

> catalog/mailhive (folder) catalog/mailhive.php

## Step 2 - modify existing files

located and open the file

> admin/includes/column\_left.php

depending on the Gambio Version proceed as following

#### Gmabio GX2 early version

find

 
    (...) 
    ' . BOX_CUSTOMERS_STATUS . '<span style="font-family: Georgia, 'Times New Roman', 'Bitstream Charter', Times, serif; font-size: 13px; line-height: 19px;">;


Add in a new line

 
    if (($_SESSION['customers_status']['customers_status_id'] == '0') && ($admin_access['module_newsletter'] == '1')) 
        echo '<ul>
                <li><a id="BOX_MAILBEEZ" href="' . xtc_href_link('mailbeez.php') . '"> MailBeez</a></li>
              </ul>';


This places a Menu-Entry in the section "Customers"

#### Gambio GX2 with Service Pack

If you are not able to find the code above, you have Service Pack 1.1 or later installed

### Option 1: add entry using a XML file

Copy the XML file from the folder structure below /extras\_gambio into the Gambio System as following:

> /system/conf/AdminMenu/menu\_mailbeez.xml

This allows Gambio to create a Menu-Entry.

### Option 2: hard-code menu entry

find

 
    # SAMPLE ITEM:


insert following code in a line above

 
    if (($_SESSION['customers_status']['customers_status_id'] == '0') && ($admin_access['module_newsletter'] == '1')) 
        echo '<ul>
                <li><a id="BOX_MAILBEEZ" href="' . xtc_href_link('mailbeez.php') . '">MailBeez</a></li>
              </ul>';


## Step 3 - add permission

run

> (shop)/mailhive.php

this will add the required permission for MailBeez for the primary admin account.

After a new login and clearing the page cache you will find MailBeez in the Section "Zusatzmodule".

If necessary add admin permission for MailBeez for secondary admin accounts as well

## Next Steps

 Now that your MailBeez installation is complete, you are encouraged to visit our [ Guide to Getting Started](http://www.mailbeez.com/documentation/tutorials/guide-to-getting-started/) to familiarize yourself with MailBeez features and functionality, and to learn how to configure and customize your MailBeez installation to suit your needs. No thanks, just take me to the [Quick Start Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-quick-start-configuration-tutorial/) No thanks, just take me to the [Comprehensive Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-comprehensive-configuration-tutorial/)

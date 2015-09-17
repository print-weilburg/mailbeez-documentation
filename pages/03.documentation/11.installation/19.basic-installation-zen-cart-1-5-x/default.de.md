---
# http://learn.getgrav.org/content/headers
title: Zen Cart 1.5.x
slug: basic-installation-zen-cart-1-5-x
# menu: Zen Cart 1.5.x
date: 01-02-2012
published: true
publish_date: 01-02-2012
# unpublish_date: 01-02-2012
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

MailHive and MailBeez and their respective installations have been successfully tested with Zen Cart v1.5.0, running on PHP 5.2.11

## Zen Cart Installation Requirements

You will need the following to be able to install and run MailBeez:

- Zen Cart v1.5.0 installed and configured
- PHP 4 or higher, compatibility tested up to PHP 5.3.5
- FTP access to your Zen Cart installation
- An FTP program, such as FileZilla
- A text editing program, such as Notepad++ to customize your email templates, if desired

The installation is straightforward and can be done in a few minutes by following a few easy steps. No Zen Cart core or template files are modified by the MailBeez installation.

## Short Installation

1. download the quickstart package and unzip it
2. navigate to the /catalog/ directory
3. copy the content into your store-root, but be careful to match your own admin directory:  
 the structure should look like this on your server:  
 /zencart-shop/zencart-admin-dir/mailbeez.php  
 /zencart-shop/mailhive/  
 /zencart-shop/mailhive.php
4. upload the zencart specific hooks located in extras\_zencart/zencart\_1.5.0 so it looks like this on your server (you find a readme.txt with more information):  
 /zencart-shop/zencart-admin-dir/includes/\*  
 /zencart-shop/includes/\*
5. now you should find a new entry “mailbeez” in your “tools” menue

## Step-by-Step Installation

To begin, please make sure you have the latest MailBeez package. If you are not sure that you have the latest release, please download the quickstart package using the link above.

### Prepare & Upload the Fileset

1. Unzip the downloaded MailBeez package to your local drive (i.e. your computer)
2. In the MailBeez fileset, navigate to **catalog > admin** and rename the admin folder to match your store’s admin folder as it appears on your server (i.e. YOUR\_ADMIN)
3. In the MailBeez fileset, navigate to **extras\_zencart > zencart\_1.5.0 > admin** and rename the admin folder to match your store’s admin folder as it appears on your server (i.e. YOUR\_ADMIN)
4. Using your FTP program, upload the **contents** of the catalog folder to your store’s root directory. **Do not upload the catalog folder itself.** The contents to be uploaded to your store’s root directory are as follows: - mailhive.php file
- re-named admin folder and its contents
- mailhive folder and its contents
5. Using your FTP program, upload the **contents** of the zencart\_1.5.0 folder to your store’s root directory. **Do not upload the zencart\_1.5.0 folder itself.** The contents to be uploaded to your store’s root directory are as follows: - re-named admin folder and its contents
- includes folder and its contents

### Install MailBeez in the Admin

1. Log in to your store admin and navigate to Tools > MailBeez. Click the “Install” button:  
[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.de/images/doc/installation/zencart/zc_install_mailhive.png&w=270&h=134&zc=1&q=100 "Install the MailBeez MailHive")](http://www.mailbeez.de/images/doc/installation/zencart/zc_install_mailhive.png "Install the MailBeez MailHive")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)
2. MailBeez has now been installed into your database and the MailBeez dashboard is now visible:  
[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.de/images/doc/installation/zencart/zc_intstall_mb_interface.png&w=270&h=253&zc=1&q=100 "MailBeez Dashboard")](http://www.mailbeez.de/images/doc/installation/zencart/zc_intstall_mb_interface.png "MailBeez Dashboard")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)
3. In the MailBeez dashboard, navigate to the MailBeez Modules tab:  
[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.de/images/doc/installation/zencart/zc_install_mb_tab.png&w=270&h=127&zc=1&q=100 "MailBeez Modules Tab")](http://www.mailbeez.de/images/doc/installation/zencart/zc_install_mb_tab.png "MailBeez Modules Tab")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)
4. Select the module(s) you wish to install – for example, Birthday Greetings – and click the “install” button:  
[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.de/images/doc/installation/zencart/zc_intstall_birthday.png&w=270&h=86&zc=1&q=100 "Install the Birthday Module")](http://www.mailbeez.de/images/doc/installation/zencart/zc_intstall_birthday.png "Install the Birthday Module")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)
5. This completes your MailBeez installation!



### Adoption of Zen-Cart

**Quick Solution:** configure a SMTP Email Server in MailBeez > Configuration > Email Engine. This will bypass the zencart email function and give MailBeez full control for sending emails

If would like MailBeez to use its own template system to generate MailBeez email (recommended), rather than integrating with and using Zen Cart’s email template system to generate MailBeez email (default), please do the following:

- Using your FTP program, download includes/functions/functions\_email.php from your server to your local drive (i.e. your computer)
- Using a text editing program such as Notepad or Notepad++, and change it as described on:
- <http://www.zen-cart.com/showthread.php?158085-Mailbeez-After-Sales-Modules&p=1170912#post1170912>

This code change tells Zen Cart to check if the content contains a valid html tag, and if not, applies the Zen Cart template system.

## Next Steps

Now that your MailBeez installation is complete, you are encouraged to visit our [ Guide to Getting Started](http://www.mailbeez.com/documentation/tutorials/guide-to-getting-started/) to familiarize yourself with MailBeez features and functionality, and to learn how to configure and customize your MailBeez installation to suit your needs.

No thanks, just take me to the [Quick Start Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-quick-start-configuration-tutorial/)  
 No thanks, just take me to the [Comprehensive Configuration tutorial](http://www.mailbeez.com/documentation/tutorials/mailbeez-comprehensive-configuration-tutorial/)

When you’re ready to customize your email templates, have a look at our tutorials: [Customizing MailBeez Free Email Templates](http://www.mailbeez.com/documentation/tutorials/customizing-mailbeez-free-email-templates/) and [Customizing MailBeez Premium Email Templates](http://www.mailbeez.com/documentation/tutorials/customizing-mailbeez-premium-email-templates/)

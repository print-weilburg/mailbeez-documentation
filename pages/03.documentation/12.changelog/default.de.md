---
# http://learn.getgrav.org/content/headers
title: Changelog - MailBeez Grundsystem
slug: changelog
# menu: Changelog - MailBeez Grundsystem
date: 30-05-2010
published: true
publish_date: 30-05-2010
# unpublish_date: 30-05-2010
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

### [18.08.2015: VERSION 3.2.0]

Enhancements

- PHP5.6 compatiblity

Bugfixes

- PHP5.6 compatiblity

### [11.08.2015: VERSION 3.1.2]

Enhancements

- shopvoting 4.03
- support for custom email main templates to avoide overwriting with updates  
 (default\_email.html.tpl will be overwritten -> rename into email.html.tpl)
- framework refactoring for using constants

Bugfixes

- related to shopvoting module

### [02.07.2015: VERSION 3.1.1]

Enhancements

- shopvoting 4.01

Bugfixes

- related to shopvoting module

### [29.06.2015: VERSION 3.1.0]

Enhancements

- integrated api framework config\_api
- shopvoting 4.0 responsive

Bugfixes

- removed shorttag <?

### [25.06.2015: VERSION 3.0.2b]

Enhancements

- integrated api framework config\_api

Bugfixes

- fixed coupon value count query

### [16.06.2015: VERSION 3.0.2a]

Enhancements

- support for profiling engine

Bugfixes

- fixed issue with cache gc loop

### [11.06.2015: VERSION 3.0.1]

Enhancements

- dashboard loading and caching

Bugfixes

- tour on gambio 2.3

### [11.06.2015: VERSION 3.0.0]

Enhancements

- MailBeez Tour
- Dashboard Ajax widgets with caching to improve loading times
- framework enhancements
- template based customizable opt-out page (DE/EN)
- Newsletter2Go bouncehandling
- Modified-Shop 2.0 ready

Bugfixes

- -

### [29.05.2015: VERSION 2.9.9-7]

Enhancements

- introduction of system status bar showing relevant number of customers
- exclude @marketplace.amazon customer from beeing counted for subscription
- tour alpha / hopscotch
- framework enhancements

Bugfixes

- shoprating bug when module was installed and main module installed

### [06.05.2015: VERSION 2.9.9-6]

Bugfixes

- smarty 3 backwards compatiblity fix
- shopvoting gambio compatibility improvements

### [30.04.2015: VERSION 2.9.9-6]

Enhancements:

- Gambio 2.3 Integration ready

Bugfixes

- Newsletter2Go SenderName
- typos

### [01.04.2015: VERSION 2.9.9-5]

Enhancements:

- shopvoting V3.58

Bugfixes

- fixed issue with SSL

### [25.03.2015: VERSION 2.9.9-4]

Enhancements:

- improved EN language string in shopvoting module
- support for osc2.3.3 config cache addon

Bugfixes

- fixed check block query bug
- fixed zencart bug with shopvoting module

### [23.03.2015: VERSION 2.9.9-3]

Enhancements:

- allover performance improvements
- improved caching for apps.mailbeez.com API
- improved commerce-seo compatiblity
- improved Gambio Integration
- improved customer insight V2.71
- shopvoting V3.57
- framework enhancements

Bugfixes

- removed PHP5.4 warning
- fixed bug when testing PHPMailer SMTP

### [10.02.2015: VERSION 2.9.9]

Enhancements:

- added shoprating module latest version
- added support for commerce-seo 2.1
- added UTF-8 support (Gambio 2.1, osCommerce 2.3.4)
- added missing language constants for Gambio 2.1
- improved clicktracker integration instructions

Bugfixes

- fixed issues with throttling
- fixed typos
- fixed PHP5.2 compatibility bug in cloudbeez api

### [05.01.2015: VERSION 2.9.8-7]

Enhancements:

- newsletter2go integration set up through api
- renamed cloudbeez.com > apps.mailbeez.com

Bugfixes

- fixed issues with Gambio userclasses
- fixed visual bug in statsbar

### [15.12.2014: VERSION 2.9.8-6]

Enhancements:

- added garbage collection for mailbeez\_process

### [12.12.2014: VERSION 2.9.8-5]

Enhancements:

- framework enhancements

Bugfixes

- fixed session cache issue

### [02.12.2014: VERSION 2.9.8-4]

Bugfixes

- fixed compatibility with PHP5.2

### [02.12.2014: VERSION 2.9.8-3]

Enhancements:

- improved newsletter2go integration (UTF-8 support)

Bugfixes

- several

### [26.11.2014: VERSION 2.9.8-2]

Bugfixes

- several

### [25.11.2014: VERSION 2.9.8-2]

Bugfixes:

- mh\_smarty\_fetch() compatibility with older versions of e.g. list\_engine

### [20.11.2014: VERSION 2.9.8-1]

Bugfixes:

- handling of CURL connection issues

### [20.11.2014: VERSION 2.9.8]

Enhancements:

- warning when PHP5.4
- check to avoid sending empty emails on PHP5.4
- added smarty 3 as default template engine, compatibility with smarty 2.6
- ready for cloudbeez.com beta testing

Bugfixes:

- fixed STRICT warnings
- removed duplicate GambioGX2 overload /user\_classes/overloads/ApplicationTopExtenderComponent/MailBeezAnalyticsClicktracker.inc.php

### [02.10.2014: VERSION 2.9.7-3]

Bugfixes:

- fixed issue with installer on zencart

### [20.09.2014: VERSION 2.9.7-2]

Bugfixes:

- fixed issue causing the email engine setting was reset

### [20.09.2014: Version 2.9.7-1]

Enhancements:

- improved version check notifications

Bugfixes:

- fixed query issue of data quality check

### [19.09.2014: Version 2.9.7]

Enhancements:

- added integration with Newsletter2Go
- added DB query watchdog to automatically kill processes after 60s (configurable)
- integrated cloudloader installer and updater
- improved customer insight order handling
- improved notification system
- added data quality widget
- allow overrides for $GLOBALS['mh\_template\_replace\_variables\_common']

Bugfixes:

- fixed bug with clicktracker

### [01.09.2014: Version 2.9.6]

silent release

Enhancements:

- improved Beez-O-Graph to show ordervalue per day
- enable filterbeez to add preview-content in visual editor
- added check for “DOMDocument” to system check
- improved version check
- updated jquery flot, jquery timeago
- fixed warning in kcfinder integration
- Framework enhancements, preparing for cloudloader

Bugfixes:

- classloader warning

### [17.02.2014: Version 2.9.5]

Bugfixes:

- fixed analytics bar division by 0 error
- fixed image path error

### [15.02.2014: Version 2.9.4]

Enhancements:

- improved mobile statistics
- improved Commerce:SEO compatibility
- improved template engine for upcoming integrations
- framework enhancements
- admin menu plugin for osCommerce 2.3.3.x
- new simplified update procedure

Bugfixes:

- fixed compatiblity with Gambio GX1

### [23.01.2014: Version 2.9.3]

Enhancements:

- commerce SEO V2Next compatibility
- framework enhancements
- improved CRE Loaded 6.x compatibility
- support for ZenCart 1.5.2RC (mysqli)
- smarty 3.1 support
- improve html code parsing for Outlook compatibility (width and heights attributes are added if dimensions were given only in style attribute)

Bugfixes:

- fixed included birthday module

### [04.12.2013: Version 2.9.2]

Enhancements:

- added delivered stats (requires bouncehive installed to handled bounces)

Bugfixes:

- fixed errors of level notice where constants not have been defined
- fixed a bug that prevented the installation of mailbeez when the beezdesk crm customer insight module was already in the fileset

### [20.11.2013: Version 2.9.1]

Enhancements:

- one bug down

Bugfixes:

- fixed a bug with the “run module” button

### [20.11.2013: Version 2.9]

Same as V2.8.10 – but fixing issue with version number

### [19.11.2013: Version 2.8.10]

Enhancements:

- compatibility improvements with responsive template manager
- improved MailBeez Analytics summary to recognise Simulation/Production mode
- improved support for https
- added {$module\_code} template variable

Bugfixes:

- fixed bug that prevented updating modules (, / . in version number)
- fixed bug that caused layout incompatibility with Outlook
- fixed installation hint for mouseflow integration
 


### [30.10.2013: Version 2.8.9]

Enhancements:

- none

Bugfixes:

- fixed bug that prevented tracking of email opens
- fixed bug that prevented MailBeez from updating itself
 


### [30.10.2013: Version 2.8.8]

Enhancements:

- improved compatibility with Gambio
- added suhosin compatibility fix (/mailhive/common/local/suhosin\_compatibility.php )

Bugfixes:

- none
 


### [29.10.2013: Version 2.8.7]

Enhancements:

- improved framework

Bugfixes:

- fixed an issue with mixing ssl, nonssl requests and servers with configure x-frame-options
 


### [25.10.2013: Version 2.8.6]

Enhancements:

- improved framework
- enhanced MailBeez Analytics to analyse and report Email openings on mobile devices
- automatically generate txt version from html email if txt template is empty

Bugfixes:

- none
 


### [20.10.2013: Version 2.8.5]

Enhancements:

- improved support for https in clicktracker
- added support for upcoming pro features (visual editor, responsive emails, mobile preview)
- dropped support for mailbeez 1.x template variables like “$firstname” (since 2.x {$firstname} )
- enhanced main template
- several framework enhancements for improved performance and support for upcoming premium features

Bugfixes:

- fixed issue with clicktracker url rewrites
- fixed character issues in dashboard news widget
 


### [14.08.2013: Version 2.8.0]

Enhancements:

- added MailBeez Analytics Summary View on Dashboard
- improved clicktracker to support rewritten urls
- improved clicktracker order tracking
- Framework improvements: integrated firelogger / firephp support, systemcheck
- added SQL\_NO\_CACHE to check queries
- improved email engine
- improved template engine to remove UTF-8 BOM and marker character in input, if present.
- added DB index to improve performance
- BeezDesk CRM ready

Bugfixes:

- fixed minor codeing errors
- fixed zencart 1.5 compatibility issue
- fixed issue with currencies class support
 


### [12.03.2013: Version 2.7.5]

Enhancements:

- improved version check (performance, more meaningful messages)

Bugfixes:

- Google Analytics Dashboard Widget: fixed installation routine
- Google Analytics Dashboard Widget: remove error when there is not data
 


### [22.02.2013: Version 2.7.4]

Enhancements:

- improved Email Encoding handling (automatic detection / manual setting / adopted main template)
- added PHPMailer Debug setting
- added PHPMailer txt wordwrap configuration setting
- added option to disable stylesheet to inline CSS conversion (requires PHP5)
- added option to control PHP Memory Limit (if possible to set)
- added option to control PHP Process time Limit (if possible to set)
- added option to control PHP Ignore User Abort
- added check for inconsistent order db
- added support for modified-shop

Bugfixes:

- fixed icon path in admin which could cause php errorlog entries
- fixed error where $request\_profiler is not defined

For updating Versiones before 2.7.2 please apply the upgrade pack for MailBeez V2.5.  
 For updating Versions 2.7.2 and 2.7.3 please apply the upgrade pack for MailBeez 2.7.2

### [17.01.2013: Version 2.7.3]

Enhancements:

- Framework improvements for future features
- allocated memory is shown in browser title when running mailhive.php manually

Bugfixes:

- removed warnings
- fixed issues with check method
- fixed admin SSL issue
- strip html tags from subject

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.7.x)

### [14.12.2012: Version 2.7.2 IMPORTANT]

Enhancements:

- support for Holbi Trueloaded oscommerce fork
- Framework improvements for future features

Bugfixes:

- **IMPORTANT:** fixed high memory usage
- fixed module incompatibilities

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.7.x)

### [06.12.2012: Version 2.7.1]

Enhancements:

- json support for servers w/o json extension
- localization of documentation and update links (www.mailbeez.de for german users)
- warning for incompatible modules

Bugfixes:

- module incompatibilities

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6.x)

### [30.11.2012: Version 2.7.0]

Enhancements:

- improved html basic template with http://htmlemailboilerplate.com/
- generic UTF-8 encoding for email content & subject
- added option to control UTF-8 encoding of subject
- automatic literal-tags are added for stylesheets
- added Emogrifier class to convert CSS to inline styles http://www.pelagodesign.com/sidecar/emogrifier/
- added support for editor shortcodes for visual template editor
- enhanced email engine to support custom message-ids
- general framework enhancements (added fineuploader, ckeditor, kcfinder, codemirror, jquery-easyui)
- sending process does not stop on user abort
- Gambio Menu xml Plugin

Bugfixes:

- Bugfix Clicktracker – openings not captured
- fixed issues with installation of dashboard modules
- fixed issues with filter loader
- fixed issues with email validation on PHP 4
- fixed issues with bouncehandling
- fixed issues with Google Analytics Dashboard Widget

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6.x)

### [05.09.2012: Version 2.6.5]

Enhancements:

- Improved compatibility of PHPMailer
- Improved handling of invalid email addresses w/o stopping PHPMailer
- PHP Mailer default Chartset UTF-8
- improved support for SSL
- improved english wording (thanks to kelly)
- added index to tracking table (automatically)

Bugfixes:

- bugfix for error on Dashboard
- Respect the “Send copy” setting in simulation mode
- iteration check bugfix
- bugfix for config\_cron\_simple support
- bugfix for WP Online Store support
- bugfix for clearing template\_c directory, which have cause that emails did not show latest changes

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6.x)

### [09.05.2012: Version 2.6.2]

Bugfixes:

- setting PHPMailer as email engine caused an error when [Bounce Handling](http://www.mailbeez.de/dokumentation/configbeez/config_bouncehive_advanced/) is not installed (will be officially released soon)
- fixed an incompatibility with the newsletter module

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6 or V2.6.1)

### [08.05.2012: Version 2.6.1]

Bugfixes:

- on some carts HEADING\_TITLE was overwritten by MailBeez – fixed
- Mouseflow include caused an error – fixed
- added MailBeez Analytics includes for CRE Loaded / LoadedCommerce and Zen-Cart

For updating please apply the upgrade pack for MailBeez V2.5

### [05.05.2012: Version 2.6]

MailBeez Version 2.6 is a major release with many improvements:

- MailBeez Analytics for tracking of open / click / purchases
- Enhanced Beez-O-Graph with pop-ups
- Google Analytics Dashboard Integration: see how GA tracks MailBeez Campaigns
- Google Analytics URL rewrites in txt format (configurable)
- Optional Bounce Handling (hard/soft bounces)
- Integrated Email Engine with DKIM support (requires PHP5)
- Email validation (PHP5) – no more stops with invalid email addresses
- Spam Compliance built-in (newsletter check / opt-out behaviour)
- Control for opt-out link behaviour: Global or module
- restart simulation from any page
- Framework enhancements, performance
- enhanced certificate management for premium modules
- Mouseflow Integration pre-installed (find a coupon for 500 credits in the admin)
- [Mouseflow Integration](http://www.mailbeez.com/documentation/configbeez/config_mouseflow/ "Mouseflow") pre-installed (find a coupon for 500 credits in the MailBeez configuration module)
- PHP5.3 ready
- Compatibility with WP Online Store for WordPress
- Compatibility with SEO Mercari

Bugfixes:

- In Simulation Mode the “send test email” function did not accept the entered email address, but sent always to the configured copy-to / simulation-to email
- Opt-Out links now contain the mode: Before the an opt-out coming from a production email was counted as simulation opt-out when MailBeez was switched back into simulation mode
- minor bugs

### [01.02.2012 Version 2.5]

- Compatibility with ZenCart 1.5.0

### [10.09.2011 Version 2.5]

Enhancements:

- “un-block” feature – customers can unblock in case of mistake
- “Kill Process” Button to stop long sending processes in case of mistake (configuration > process control)
- design improvements and new icons
- Status-Indicator production / simulation
- generic framework enhancements
- new default layout, 600px width
- ZenCart: option to override Zencarts email template system to give full layout control to MailBeez
- ZenCart: With using Zencarts email templates the system tries to use email/email\_template\_mailbeez.html. If that does not exist, the email\_template\_default.html is applied
- Support for CRE 6.2 (not tested)
- Support for commerce:SEO
- Copyright Footer, remove with [MailBeez Copyright Remover Certificate](http://www.mailbeez.com/documentation/configbeez/config_copyright_remover/ "MailBeez Copyright Remover Certificate")

Bugfixes:

- option to try to fix “double-dot” bug (configuration > email engine)

### [25.08.2011 Version 2.4]

v2.4

- Bugfix-Release

### [11.08.2011 Version 2.3]

v2.3

- Winback-O-Meter shows the rate of sent Winback Emails to resulting Orders
- Beez-O-Graph shows recent statistics for Emails sent and opt-outs
- Dashboard Layout Improvements (thanks to Pete)

bugfix:

- avoiding process locking when sending test emails

### [02.08.2011 Version 2.2]

v2.2

- technical framework enhancements (functionality, performance, refactoring)
- MailBeez Process Control – avoids overlapping mailhive processes (technical)
- support of complex modules (expand / collapse)
- improvements of the admin interface (translation & layout of common buttons)
- review-o-meter: shows rate of reviews : customers on dashboard
- Support for oscMax 2.5 and Gambio Gx 2

bugfix:

- many minor bugs…

### [29.04.2011 Version 2.1]

v2.1

- technical framework enhancements (functionality, performance, refactoring)
- improvements of the admin interface
- inline version checker (requires CURL)
- new external version checker in popup
- “Filter”-tab renamed into “Filter & Helper”
- moved “configuration” tab

bugfix:

- opt-url is now “URL rewriter save”
- many minor bugs…

### [09.02.2011 Version 2.02]

bugfix:

- installation failure due to configuration caching

### [08.02.2011 Version 2.01]

bugfix:

- compatibility with 1.x template format in subject templates “$firstname $lastname” was not replaced

### [02.02.2011 Version 2.0]

enhancements:

- Tabbed admin interface with Dashboard, Reports, Filters - Reports - Event log Viewer: see, when mailhive was called
- Tracking log Viewer: see a list of sent emails
- Opt-out Viewer: see a list how has opt-out
- Filters - optional: newsletter subscribers only
- support for customer made filters
- multi language support for admin interface (EN, DE included)
- Platform support for osCommerce 2.3
- Smarty.net Template engine (smarty 2 included, compatible with smarty 3)
- automatic upgrade w/o need to remove modules
- Configurable “Medium” and “Source” for Google Analytics integration
- Advanced Simulations: - Tracking of Sendings in Simulation Mode
- Opt-Outs in Simulation Mode
- Simulations are marked with [SIM]
- Event-Logger
- Validation check of data (in some cases e.g. email adress is missing, which caused the module to stop)
- Configurable early check: choose yourself if you would like to see how already got the email
- Check-Box options in modules
- silent mode for mailhive.php: add “&silent=true” to url to oppress output e.g. for cronjob

bugfix:

- Date calculation works now for negative number of days
- zencart: no more session id in emails
- zencart: fixed 404 when sending a test email due to session-id added

### [16.09.2010 Version 1.7]

enhancements:

- added new functions used by latest version of modules
- Platform support for DigiStore

bugfix:

- Path settings

### [15.09.2010 Version 1.6a - silent update, no new version]

bugfix:

- ZenCart: CeeBox Popups didn’t work any longer (late nights…)

### [13.09.2010 Version 1.6]

enhancements

- Google Analytics now active by default for all modules
- Platform support for osCMax, xtc-modified and Gambio GX

bugfix:

- fixed Image-Path for ZenCart
- mailhive.php: disabled GZIP for ZenCart (cause for “white popups” issue)
- mailhive.php: set error-output for ZenCart (ZenCart disables all error messages….)

### [02.09.2010 Version 1.5]

enhancements

- opt-out/block feature for emails
- build-in update reminder
- Zen-Cart: “drop-in” installation without modifying any files!

### [20.08.2010 Version 1.4]

enhancements

- Google Analytics Integration – track MailBeez in GA
- CeeBox Popups can be disabled in case of compatibility issues

### [26.07.2010 Version 1.3]

bugfix:

- zencart table prefix now in installation (thanks to [alray10](http://www.zen-cart.com/forum/showthread.php?t=158085))
- zencart, xtcommerce simulate DIR\_WS\_HTTP\_CATALOG (thanks to [BeautyHealth.com.cy](http://www.zen-cart.com/forum/showthread.php?t=158085&page=2))

enhancements

- $storename, $storeurl now global replacements

### [21.06.2010 Version 1.2]

- support of SSL in admin (otherwise CeeBox popups are emtpy
- set new doctype in admin/mailbeez.php to avoid issues with CeeBox in MS IE

### [28.05.2010 Version 1.1a]

- config cache cleaner in admin module added

### [27.05.2010 Version 1.1]

- initial version of MailBeez

### [2010-01-20  Version 1.0 - productive Prototype]

- First Automatic Trigger Email Campaign send

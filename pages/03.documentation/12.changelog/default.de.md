---
# http://learn.getgrav.org/content/headers
title: Changelog - MailBeez Grundsystem
slug: changelog
# menu: Changelog - MailBeez Grundsystem
date: 30-05-2010
published: true
publish_date: 30-05-2010
# unpublish_date: 30-05-2010
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
markdown_extra: true 
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

# changelog

<div class="changelog" markdown="1" >

### v3.2.0
#### 18.08.2015

1. [](#improved)
    * PHP5.6 compatiblity

### v3.1.2
#### 11.08.2015

1. [](#new)
    * support for custom email main templates to avoide overwriting with updates  
 (default\_email.html.tpl will be overwritten -> rename into email.html.tpl)
1. [](#improved)
    * framework refactoring for using constants
    * shopvoting 4.03
3. [](#bugfix)
    * related to shopvoting module

### v3.1.1
#### 02.07.2015

1. [](#improved)
    * shopvoting 4.01
3. [](#bugfix)
    * related to shopvoting module

### v3.1.0
#### 29.06.2015

1. [](#improved)  
    * integrated api framework config\_api
    * shopvoting 4.0 responsive
3. [](#bugfix)
    * removed php shorttag 

### v3.0.2a
#### 25.06.2015

1. [](#new)
    * integrated api framework config\_api
3. [](#bugfix)
    * fixed coupon value count query

### v3.0.2a
#### 16.06.2015

1. [](#new)
    * support for profiling engine
3. [](#bugfix)
    * fixed issue with cache gc loop

### v3.0.1
#### 11.06.2015

1. [](#improved)
    * dashboard loading and caching
3. [](#bugfix)
    * tour on gambio 2.3

### v3.0.0
#### 11.06.2015

1. [](#new)
    * MailBeez Tour
    * Newsletter2Go bouncehandling
1. [](#improved)
    * Modified-Shop 2.0 ready
    * framework enhancements
    * template based customizable opt-out page (DE/EN)
    * Dashboard Ajax widgets with caching to improve loading times

### v2.9.9-7
#### 29.05.2015

1. [](#new)
    * introduction of system status bar showing relevant number of customers
    * tour alpha / hopscotch
1. [](#improved)
    * exclude @marketplace.amazon customer from beeing counted for subscription
    * framework enhancements
3. [](#bugfix)
    * shoprating bug when module was installed and main module installed

### v2.9.9-6
#### 06.05.2015

1. [](#improved)
    * shopvoting gambio compatibility improvements
3. [](#bugfix)
    * smarty 3 backwards compatiblity fix

### v2.9.9-6
#### 30.04.2015

1. [](#improved)
    * Gambio 2.3 Integration ready
3. [](#bugfix)
    * Newsletter2Go SenderName
    * typos

### v2.9.9-5
#### 01.04.2015

1. [](#improved)
    * shopvoting V3.58
3. [](#bugfix)
    * fixed issue with SSL

### v2.9.9-4
#### 25.03.2015

1. [](#improved)
    * improved EN language string in shopvoting module
    * support for osc2.3.3 config cache addon
3. [](#bugfix)
    * fixed check block query bug
    * fixed zencart bug with shopvoting module

### v2.9.9-3
#### 23.03.2015

1. [](#improved)
    * allover performance improvements
    * improved caching for apps.mailbeez.com API
    * improved commerce-seo compatiblity
    * improved Gambio Integration
    * improved customer insight V2.71
    * shopvoting V3.57
    * framework enhancements
3. [](#bugfix)
    * removed PHP5.4 warning
    * fixed bug when testing PHPMailer SMTP

### v2.9.9
#### 10.02.2015

1. [](#new)
    * added support for commerce-seo 2.1
    * added UTF-8 support (Gambio 2.1, osCommerce 2.3.4)
    * added missing language constants for Gambio 2.1
1. [](#improved)
    * improved clicktracker integration instructions
    * added shoprating module latest version
3. [](#bugfix)
    * fixed issues with throttling
    * fixed typos
    * fixed PHP5.2 compatibility bug in cloudbeez api

### v2.9.8-7
#### 05.01.2015



1. [](#improved)
    * renamed cloudbeez.com > apps.mailbeez.com
    * newsletter2go integration set up through api
3. [](#bugfix)
    * fixed issues with Gambio userclasses
    * fixed visual bug in statsbar

### v2.9.8-6
#### 15.12.2014

1. [](#new)
    * added garbage collection for mailbeez\_process

### v2.9.8-5
#### 12.12.2014

1. [](#improved)    
    * framework enhancements
3. [](#bugfix)
    * fixed session cache issue

### v2.9.8-4
#### 02.12.2014

3. [](#bugfix)
    * fixed compatibility with PHP5.2

### v2.9.8-3
#### 02.12.2014

1. [](#improved)
    * improved newsletter2go integration (UTF-8 support)
3. [](#bugfix)
    * several

### v2.9.8-2
#### 26.11.2014

3. [](#bugfix)
    * several

### v2.9.8-2
#### 25.11.2014

3. [](#bugfix)
    * mh\_smarty\_fetch() compatibility with older versions of e.g. list\_engine

### v2.9.8-1
#### 20.11.2014

3. [](#bugfix)
    * handling of CURL connection issues

### v2.9.8
#### 20.11.2014


1. [](#new)
    * warning when PHP5.4
1. [](#improved)
    * check to avoid sending empty emails on PHP5.4
    * added smarty 3 as default template engine, compatibility with smarty 2.6
    * ready for cloudbeez.com beta testing
3. [](#bugfix)
    * fixed STRICT warnings
    * removed duplicate GambioGX2 overload /user\_classes/overloads/ApplicationTopExtenderComponent/MailBeezAnalyticsClicktracker.inc.php

### v2.9.7-3
#### 02.10.2014

3. [](#bugfix)
    * fixed issue with installer on zencart

### v2.9.7-2
#### 20.09.2014

3. [](#bugfix)
    * fixed issue causing the email engine setting was reset

### v2.9.7-1
#### 20.09.2014

1. [](#improved)
    * improved versioncheck notifications
3. [](#bugfix)
    * fixed query issue of data quality check

### v2.9.7
#### 19.09.2014

1. [](#new)
    * added integration with Newsletter2Go
    * added DB query watchdog to automatically kill processes after 60s (configurable)
    * integrated cloudloader installer and updater
    * added data quality widget
    * allow overrides for $GLOBALS['mh\_template\_replace\_variables\_common']
1. [](#improved)
    * improved customer insight order handling
    * improved notification system
3. [](#bugfix)
    * fixed bug with clicktracker

### v2.9.6
#### 01.09.2014

silent release

1. [](#new)
    * enable filterbeez to add preview-content in visual editor
    * added check for “DOMDocument” to system check
    * updated jquery flot, jquery timeago
    * fixed warning in kcfinder integration
    * Framework enhancements, preparing for cloudloader
1. [](#improved)
    * improved Beez-O-Graph to show ordervalue per day
    * improved version check
3. [](#bugfix)
    * classloader warning

### v2.9.5
#### 17.02.2014

3. [](#bugfix)
    * fixed analytics bar division by 0 error
    * fixed image path error

### v2.9.4
#### 15.02.2014

1. [](#new)
    * admin menu plugin for osCommerce 2.3.3.x
1. [](#improved)
    * improved mobile statistics
    * improved Commerce:SEO compatibility
    * improved template engine for upcoming integrations
    * framework enhancements
    * new simplified update procedure
3. [](#bugfix)
    * fixed compatiblity with Gambio GX1

### v2.9.3
#### 23.01.2014

1. [](#new)
    * commerce SEO V2Next compatibility
    * support for ZenCart 1.5.2RC (mysqli)
    * smarty 3.1 support
1. [](#improved)
    * framework enhancements
    * improve html code parsing for Outlook compatibility (width and heights attributes are added if dimensions were given only in style attribute)
    * improved CRE Loaded 6.x compatibility
3. [](#bugfix)
    * fixed included birthday module

### v2.9.2
#### 04.12.2013

1. [](#new)
    * added delivered stats (requires bouncehive installed to handled bounces)
3. [](#bugfix)
    * fixed errors of level notice where constants not have been defined
    * fixed a bug that prevented the installation of mailbeez when the beezdesk crm customer insight module was already in the fileset

### v2.9.1
#### 20.11.2013

1. [](#improved)
    * one bug down
3. [](#bugfix)
    * fixed a bug with the “run module” button

### v2.9
#### 20.11.2013

Same as V2.8.10 – but fixing issue with version number

### v2.8.10
#### 19.11.2013

1. [](#new)
    * added {$module\_code} template variable
1. [](#improved)
    * compatibility improvements with responsive template manager
    * improved MailBeez Analytics summary to recognise Simulation/Production mode
    * improved support for https
3. [](#bugfix)
    * fixed bug that prevented updating modules (, / . version number)
    * fixed bug that caused layout incompatibility with Outlook
    * fixed installation hint for mouseflow integration
 


### v2.8.9
#### 30.10.2013

3. [](#bugfix)
    * fixed bug that prevented tracking of email opens
    * fixed bug that prevented MailBeez from updating itself
 

### v2.8.8
#### 30.10.2013

1. [](#new)
    * added suhosin compatibility fix (/mailhive/common/local/suhosin\_compatibility.php )
1. [](#improved)
    * improved compatibility with Gambio

### v2.8.7
#### 29.10.2013

1. [](#improved)
    * improved framework
3. [](#bugfix)
    * fixed an issue with mixing ssl, nonssl requests and servers with configure x-frame-options

### v2.8.6
#### 25.10.2013

1. [](#new)
    * enhanced MailBeez Analytics to analyse and report Email openings on mobile devices
    * automatically generate txt version from html email if txt template is empty
1. [](#improved)
    * improved framework

### v2.8.5
#### 20.10.2013

1. [](#new)
    * added support for upcoming pro features (visual editor, responsive emails, mobile preview)
    * dropped support for mailbeez 1.x template variables like “$firstname” (since 2.x {$firstname} )
1. [](#improved)
    * improved support for https in clicktracker
    * enhanced main template
    * several framework enhancements for improved performance and support for upcoming premium features
3. [](#bugfix)
    * fixed issue with clicktracker url rewrites
    * fixed character issues in dashboard news widget


### v2.8.0
#### 14.08.2013

1. [](#new)
    * added MailBeez Analytics Summary View on Dashboard
    * BeezDesk CRM ready
1. [](#improved)
    * improved clicktracker to support rewritten urls
    * improved clicktracker order tracking
    * Framework improvements: integrated firelogger / firephp support, systemcheck
    * added SQL\_NO\_CACHE to check queries
    * improved email engine
    * improved template engine to remove UTF-8 BOM and marker character in input, if present.
    * added DB index to improve performance
3. [](#bugfix)
    * fixed minor codeing errors
    * fixed zencart 1.5 compatibility issue
    * fixed issue with currencies class support
 


### v2.7.5
#### 12.03.2013

1. [](#improved)
    * improved version check (performance, more meaningful messages)
3. [](#bugfix)
    * Google Analytics Dashboard Widget: fixed installation routine
    * Google Analytics Dashboard Widget: remove error when there is not data


### v2.7.4
#### 22.02.2013

1. [](#new)
    * added PHPMailer Debug setting
    * added PHPMailer txt wordwrap configuration setting
    * added option to disable stylesheet to inline CSS conversion (requires PHP5)
    * added option to control PHP Memory Limit (if possible to set)
    * added option to control PHP Process time Limit (if possible to set)
    * added option to control PHP Ignore User Abort
    * added check for inconsistent order db
    * added support for modified-shop
1. [](#improved)
    * improved Email Encoding handling (automatic detection / manual setting / adopted main template)
3. [](#bugfix)
    * fixed icon path in admin which could cause php errorlog entries
    * fixed error where $request\_profiler is not defined

For updating Versiones before 2.7.2 please apply the upgrade pack for MailBeez V2.5.  
For updating Versions 2.7.2 and 2.7.3 please apply the upgrade pack for MailBeez 2.7.2

### v2.7.3
#### 17.01.2013

1. [](#new)
    * allocated memory is shown in browser title when running mailhive.php manually
1. [](#improved)
    * Framework improvements for future features
3. [](#bugfix)
    * removed warnings
    * fixed issues with check method
    * fixed admin SSL issue
    * strip html tags from subject

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.7.x)

### v2.7.2 IMPORTANT
#### 14.12.2012

1. [](#new)
    * support for Holbi Trueloaded oscommerce fork
1. [](#improved)
    * Framework improvements for future features
3. [](#bugfix)
    * **IMPORTANT:** fixed high memory usage
    * fixed module incompatibilities

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.7.x)

### v2.7.1
#### 06.12.2012

1. [](#new)
    * json support for servers w/o json extension
    * warning for incompatible modules
1. [](#improved)
    * localization of documentation and update links (www.mailbeez.de for german users)
3. [](#bugfix)
    * module incompatibilities

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6.x)

### v2.7.0
#### 30.11.2012

1. [](#new)
    * generic UTF-8 encoding for email content & subject
    * added option to control UTF-8 encoding of subject
    * automatic literal-tags are added for stylesheets
    * added Emogrifier class to convert CSS to inline styles http://www.pelagodesign.com/sidecar/emogrifier/
    * added support for editor shortcodes for visual template editor
    * enhanced email engine to support custom message-ids
    * sending process does not stop on user abort
    * Gambio Menu xml Plugin
1. [](#improved)
    * improved html basic template with http://htmlemailboilerplate.com/
    * general framework enhancements (added fineuploader, ckeditor, kcfinder, codemirror, jquery-easyui)
3. [](#bugfix)
    * Bugfix Clicktracker – openings not captured
    * fixed issues with installation of dashboard modules
    * fixed issues with filter loader
    * fixed issues with email validation on PHP 4
    * fixed issues with bouncehandling
    * fixed issues with Google Analytics Dashboard Widget

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6.x)

### v2.6.5
#### 05.09.2012

1. [](#new)
    * PHP Mailer default Chartset UTF-8
    * added index to tracking table (automatically)
1. [](#improved)
    * improved compatibility of PHPMailer
    * improved handling of invalid email addresses w/o stopping PHPMailer
    * improved support for SSL
    * improved english wording (thanks to kelly)
3. [](#bugfix)
    * bugfix for error on Dashboard
    * Respect the “Send copy” setting in simulation mode
    * iteration check bugfix
    * bugfix for config\_cron\_simple support
    * bugfix for WP Online Store support
    * bugfix for clearing template\_c directory, which have cause that emails did not show latest changes

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6.x)

### v2.6.2
#### 09.05.2012

3. [](#bugfix)
    * setting PHPMailer as email engine caused an error when [Bounce Handling](/documentation/configbeez/config_bouncehive_advanced/) is not installed (will be officially released soon)
    * fixed an incompatibility with the newsletter module

For updating please apply the upgrade pack for MailBeez V2.5 (even if you are running MailBeez V2.6 or V2.6.1)

### v2.6.1
#### 08.05.2012

3. [](#bugfix)
    * on some carts HEADING\_TITLE was overwritten by MailBeez – fixed
    * Mouseflow include caused an error – fixed
    * added MailBeez Analytics includes for CRE Loaded / LoadedCommerce and Zen-Cart

For updating please apply the upgrade pack for MailBeez V2.5

### v2.6
#### 05.05.2012

MailBeez Version 2.6 is a major release with many improvements:

1. [](#new)
    * MailBeez Analytics for tracking of open / click / purchases
    * Enhanced Beez-O-Graph with pop-ups
    * Google Analytics Dashboard Integration: see how GA tracks MailBeez Campaigns
    * Google Analytics URL rewrites in txt format (configurable)
    * Optional Bounce Handling (hard/soft bounces)
    * Integrated Email Engine with DKIM support (requires PHP5)
    * Email validation (PHP5) – no more stops with invalid email addresses
    * Spam Compliance built-in (newsletter check / opt-out behaviour)
    * Control for opt-out link behaviour: Global or module
    * restart simulation from any page
    * Framework 1. [](#new), performance
    * Mouseflow Integration pre-installed (find a coupon for 500 credits in the admin)
    * [Mouseflow Integration](http://www.mailbeez.com/documentation/configbeez/config_mouseflow/ "Mouseflow") pre-installed (find a coupon for 500 credits in the MailBeez configuration module)
    * Compatibility with WP Online Store for WordPress
    * Compatibility with SEO Mercari
1. [](#improved)
    * enhanced certificate management for premium modules
    * PHP5.3 ready
3. [](#bugfix)
    * In Simulation Mode the “send test email” function did not accept the entered email address, but sent always to the configured copy-to / simulation-to email
    * Opt-Out links now contain the mode: Before the an opt-out coming from a production email was counted as simulation opt-out when MailBeez was switched back into simulation mode
    * minor bugs

### v2.5
#### 01.02.2012

1. [](#new)
    * Compatibility with ZenCart 1.5.0

### v2.5
#### 10.09.2011

1. [](#new)
    * “un-block” feature – customers can unblock in case of mistake
    * “Kill Process” Button to stop long sending processes in case of mistake (configuration > process control)
    * Status-Indicator production / simulation
    * new default layout, 600px width
    * ZenCart: option to override Zencarts email template system to give full layout control to MailBeez
    * ZenCart: With using Zencarts email templates the system tries to use email/email\_template\_mailbeez.html. If that does not exist, the email\_template\_default.html is applied
    * Support for CRE 6.2 (not tested)
    * Support for commerce:SEO
    * Copyright Footer, remove with [MailBeez Copyright Remover Certificate](http://www.mailbeez.com/documentation/configbeez/config_copyright_remover/ "MailBeez Copyright Remover Certificate")
1. [](#improved)
    * generic framework enhancements
    * design improvements and new icons
3. [](#bugfix)
    * option to try to fix “double-dot” bug (configuration > email engine)

### v2.4
#### 25.08.2011

3. [](#bugfix)
    * Bugfix-Release

### v2.3
#### 11.08.2011

1. [](#new)
    * Winback-O-Meter shows the rate of sent Winback Emails to resulting Orders
    * Beez-O-Graph shows recent statistics for Emails sent and opt-outs
    * Dashboard Layout Improvements (thanks to Pete)
3. [](#bugfix)
    * avoiding process locking when sending test emails

### v2.2
#### 02.08.2011

1. [](#new)
    * MailBeez Process Control – avoids overlapping mailhive processes (technical)
    * support of complex modules (expand / collapse)
    * review-o-meter: shows rate of reviews : customers on dashboard
    * Support for oscMax 2.5 and Gambio Gx 2
1. [](#improved)
    * technical framework enhancements (functionality, performance, refactoring)
    * improvements of the admin interface (translation & layout of common buttons)
3. [](#bugfix)
    * many minor bugs…

### v2.1
#### 29.04.2011

1. [](#new)
    * inline version checker (requires CURL)
    * new external version checker in popup
1. [](#improved)
    * technical framework enhancements (functionality, performance, refactoring)
    * improvements of the admin interface
    * moved “configuration” tab
    * “Filter”-tab renamed into “Filter & Helper”
3. [](#bugfix)
    * opt-url is now “URL rewriter save”
    * many minor bugs…

### v2.02
#### 09.02.2011

3. [](#bugfix)
    * installation failure due to configuration caching

### v2.01
#### 08.02.2011

3. [](#bugfix)
    * compatibility with 1.x template format in subject templates “$firstname $lastname” was not replaced

### v2.0
#### 02.02.2011

1. [](#new)
    * Tabbed admin interface with Dashboard, Reports, Filters - Reports - Event log Viewer: see, when mailhive was called
    * Tracking log Viewer: see a list of sent emails
    * Opt-out Viewer: see a list how has opt-out
    * Filters - optional: newsletter subscribers only
    * support for customer made filters
    * multi language support for admin interface (EN, DE included)
    * Platform support for osCommerce 2.3
    * Smarty.net Template engine (smarty 2 included, compatible with smarty 3)
    * automatic upgrade w/o need to remove modules
    * Configurable “Medium” and “Source” for Google Analytics integration
    * Advanced Simulations: - Tracking of Sendings in Simulation Mode
    * Opt-Outs in Simulation Mode
    * Simulations are marked with [SIM]
    * Event-Logger
    * Validation check of data (in some cases e.g. email adress is missing, which caused the module to stop)
    * Configurable early check: choose yourself if you would like to see how already got the email
    * Check-Box options in modules
    * silent mode for mailhive.php: add “&silent=true” to url to oppress output e.g. for cronjob
3. [](#bugfix)
    * Date calculation works now for negative number of days
    * zencart: no more session id in emails
    * zencart: fixed 404 when sending a test email due to session-id added

### v1.7
#### 16.09.2010

1. [](#new)
    * added new functions used by latest version of modules
    * Platform support for DigiStore
3. [](#bugfix)
    * Path settings

### v1.6a - silent update, no new version
#### 15.09.2010

3. [](#bugfix)
    * ZenCart: CeeBox Popups didn’t work any longer (late nights…)

### v1.6
#### 13.09.2010

1. [](#new)
    * Google Analytics now active by default for all modules
    * Platform support for osCMax, xtc-modified and Gambio GX
3. [](#bugfix)
    * fixed Image-Path for ZenCart
    * mailhive.php: disabled GZIP for ZenCart (cause for “white popups” issue)
    * mailhive.php: set error-output for ZenCart (ZenCart disables all error messages….)

### v1.5
#### 02.09.2010

1. [](#new)
    * opt-out/block feature for emails
    * build-in update reminder
    * Zen-Cart: “drop-in” installation without modifying any files!

### v1.4
#### 20.08.2010

1. [](#new)
    * Google Analytics Integration – track MailBeez in GA
    * CeeBox Popups can be disabled in case of compatibility issues

### v1.3
#### 26.07.2010

3. [](#bugfix)
    * zencart table prefix now in installation (thanks to [alray10(http://www.zen-cart.com/forum/showthread.php?t=158085))
    * zencart, xtcommerce simulate DIR\_WS\_HTTP\_CATALOG (thanks to [BeautyHealth.com.cy](http://www.zen-cart.com/forum/showthread.php?t=158085&page=2))
1. [](#new)
    * $storename, $storeurl now global replacements

### v1.2
#### 21.06.2010

1. [](#new)
    * support of SSL in admin (otherwise CeeBox popups are emtpy
    * set new doctype in admin/mailbeez.php to avoid issues with CeeBox in MS IE

### v1.1a
#### 28.05.2010

1. [](#new)
    * config cache cleaner in admin module added

### v1.1
#### 27.05.2010

1. [](#new)
    * initial Version of MailBeez

### v1.0 - productive Prototype
#### 20.01.2010 

1. [](#new)
    * First Automatic Trigger Email Campaign sent

</div>


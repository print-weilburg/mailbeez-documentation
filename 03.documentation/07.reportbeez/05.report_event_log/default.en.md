---
# http://learn.getgrav.org/content/headers
title: MailBeez Event Log Viewer
slug: report_event_log
# menu: MailBeez Event Log Viewer
date: 03-03-2011
published: true
publish_date: 03-03-2011
# unpublish_date: 03-03-2011
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

## The MailBeez Event Log

MailBeez tracks when MailHive is initiated, run, tested, and completed. The tracking for each of these events is displayed in a log which allows you to browse through both the recent and historical events. Delivered with the MailBeez framework software, this report helps you to see when MailHive was triggered to execute the MailBeez modules.

The report will even tell you which mode you were in when the modules were run:

- PROD - MailBeez was executed in Production Mode
- [SIM] – MailBeez was executed in Simulation Mode

### Interpreting the Data

- MAILHIVE\_RUN\_INIT – Initialization of MailHive for executing a run. An INIT w/o a COMPLETE means something went wrong
- MAILHIVE\_RUN\_COMPLETE – Run was completed
- MAILHIVE\_TEST\_INIT- Initialization of MailHive for executing a send test email. An INIT w/o a COMPLETE means something went wrong
- MAILHIVE\_TEST\_COMPLETE - Run was completed
- MAILBEEZ\_MODULE\_INIT – Initialization of a Module (when event log was configured to log this event)

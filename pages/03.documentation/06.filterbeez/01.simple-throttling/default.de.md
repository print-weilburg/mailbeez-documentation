---
# http://learn.getgrav.org/content/headers
title: Einfache Drosselung
slug: einfache-drosselung
# menu: Einfache Drosselung
date: 08-04-2011
published: true
publish_date: 08-04-2011
# unpublish_date: 08-04-2011
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

Dieses Filtermodul drosselt den Email Versand von MailBeez.

Einige Hoster schränken den Versand von Emails ein, z.B. maximal 480 Emails pro Stunde. Mit diesem Modul stellen Sie sicher, mit MailBeez immer unter diesem Limit zu bleiben.

Einfachste Installation und Konfiguration!

Wenn Sie MailBeez häufig, z.B. minütlich ausführen, müssen Sie die Einstellung “Maximal Anzahl Emails per Durchlauf” so niedrig einstellen, dass ein Durchlauf abgeschlossen ist, bevor der nächste gestartet wird. Andernfalls können sich die Versandprozesse überlappen und damit Emails in einer höheren Rate versendet werden.

Bespiel:

- MailBeez wird von einem Cronjob minütlich ausgeführt
- Der Hoster erlaubt höchsten 30 Emails pro Minute
- Daher muss “Maximal Anzahl Emails per Durchlauf” unter 30 liegen, z.B. 25

Mit dieser Einstellung wird MailBeez den Versand nach 25 Emails anhalten, was nicht länger als 1 minute dauern sollte – also bevor der nächste Durchlauf startet.

 

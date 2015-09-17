---
# http://learn.getgrav.org/content/headers
title: Commerce:SEO V2Next
slug: basic-installation-commerceseo-v2next
# menu: Commerce:SEO V2Next
date: 23-01-2014
published: true
publish_date: 23-01-2014
# unpublish_date: 23-01-2014
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

erfordert MailBeez V2.9.3+

Die Installation ist erfolgreich mit *commerce:SEO v2next CE 2.4.5* getested

Die Installation ist in wenigen Schritten erledigt:

- Die neuen Dateien übertragen
- Menü-Eintrag anlegen
- Zugriffs-Rechte für den Admin vergeben (halb automatisch)
- MailBeez per Button-Klick installieren

MailBeez verwaltet eigene Tabellen - die vorhandenen Shop-Tabellen werden nicht verändert.

## Schritt 1 - Die neuen Dateien übertragen

folgende Datei in das admin-Verzeichnis kopieren

> catalog/admin/mailbeez.php

folgende Dateien und Ordner in den Shop-Root kopieren

> catalog/mailhive (Ordner)  
>  catalog/mailhive.php

## Schritt 2 - Menü-Eintrag anlegen

### Option 1: Menü-Eintrag hard-kodieren

-- nicht update-sicher --

folgende Datei öffnen:

> admin/includes/column\_top.php

z.B. in der Zeile vor

 
    <!-- Gutscheine -->


den folgenden Code eintragen:

 
    <li><a href="mailbeez.php">MailBeez</a></li>


### Option 2: Admin Menü Eintrag mit Admin-Menü Addon anlegen

-- update-sicher --

Bitte hierzu Commerce:SEO kontaktieren.

## Step 3 - Zugriffsrechte vergeben

einmalig im Browser

> (shop-url)/mailhive.php

aufrufen.

Hierdurch werden die erforderlichen Admin-Rechten für den HAUPT-Admin vergeben.

Falls erforderlich dann Zugriffs-Rechte im Admin System für weitere Admin-user vergeben

## Weitere Schritte

 Nach der Grund-Installation hilft das Tutorial [Schnelleinstieg](http://www.mailbeez.de/dokumentation/tutorials/schnelleinstieg/) weiter, die Grundlagen von MailBeez zu verstehen. Nein Danke, bitte gleich zum Tutorial [MailBeez Konfiguration einfach](http://www.mailbeez.de/dokumentation/tutorials/mailbeez-konfiguration-einfach/) Nein Danke, bitte gleich zum Tutorial [MailBeez Konfiguration ausführlich](http://www.mailbeez.de/dokumentation/tutorials/mailbeez-konfiguration-ausfuehrlich/)

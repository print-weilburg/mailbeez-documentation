---
# http://learn.getgrav.org/content/headers
title: Trustpilot Bewertungen in Emails
slug: filter_add_trustpilot_rss
# menu: Trustpilot Bewertungen in Emails
date: 03-05-2011
published: true
publish_date: 03-05-2011
# unpublish_date: 03-05-2011
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

Fügen Sie Ihre wertvollen Trustpilot ratings automatisch in Ihre MailBeez Email Kampagnen ein – hervorragend um die Emails zur “Kundenrückgewinnung” (Winback) und “Kunden ohne Kauf” (Nopurchase) aufzuwerten.

Dieses Hilfsmodule ist Teil der [Trustpilot Integration Suite](http://www.mailbeez.com/documentation/configbeez/config_trustpilot_rss_importer/?lang=de "Trustpilot Integration Suite").

Mit der beiliegenden Standard Vorlage sehen die Bewertungen folgendermassen aus:

[![](http://www.mailbeez.com/wp-content/uploads/2011/05/default_email_template-300x289.png "default_email_template")](http://www.mailbeez.com/wp-content/uploads/2011/05/default_email_template.png)Default Template for Email Integration

 

 

### Optionen:

**Anzahl Bewertungen**  
 Anzahl Bewertungen in den Emails (Zahl)

**Mindestanzahl Sterne**  
 Nur Bewertungen mit mindestens diese Anzahl Sterne anzeigen (3-5)

**Zufällige Reihenfolge**  
 Zufällige Reihenfolge True) oder chronologische Reihenfolge (False)

 

### Anwendung:

Modul installieren und Aktvieren – vorher den Trustpilot RSS feed Importer konfigurieren und testen.

Mit folgende Platzhaltern können Sie die konfigurierte Anzahl an Bewertungen in von MailBeez generierten Emails einfügen. Die Platzhalter können an jeder beliebigen Stellen in den MailBeez Vorlagen (\*.tpl Dateien) eingefügt werden. Sollen die Bewertungen in allen Emails sichtbar sein, am besten in die Hauptvorlage einfügen

Platzhalter für die HTML-Version der Vorlage:

> `{$content.rss.trustpilot.html}`

Platzhalter für die TXT-Version der Vorlage:

> `{$content.rss.trustpilot.txt}`

Die Vorlage für die Darstellung der Bewertungen ist folgende Datei

> `rss_email_html.tpl`  
> `rss_email_txt.tpl`

welche in folgendem Ordner liegt:

> `mailhive\configbeez\config_trustpilot_rss_importer\templates`

Fortgeschrittene Benutzter können auch das Daten-Object mit den Bewertungen direkt im Email Template verwenden – Anleitung hierzu finden Sie im Modul (Admin)

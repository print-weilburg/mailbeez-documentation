---
# http://learn.getgrav.org/content/headers
title: Benachrichtigung: Bestell-Status Änderung
slug: notification_order_status
# menu: Benachrichtigung: Bestell-Status Änderung
date: 01-03-2013
published: true
publish_date: 01-03-2013
# unpublish_date: 01-03-2013
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
download:
    category: [mailbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2013/03/icon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '49 EUR'
    title_en: 'Notification: Order Status Update'
    teaser_en: 'Notify your customers about an specific order status update, e.g. to send a delivery tracking link'
    title_de: 'Benachrichtigung: Bestell-Status Änderung'
    teaser_de: 'Benachrichtigen Sie Ihre Kunden bei speziellen Bestell-Status Änderungen, z.B. um einen Link zur Paket-Verfolgung zu schicken'
    author: 'MailBeez.com'
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

Dieses praktische Module sendet bei Änderung des Bestell-Status auf einen oder mehrere konfigurierbare Status eine Benachrichtigung an den Kunden.

Optional kann das Modul nach Versand den Bestell-Status auf einen neuen, wählbaren Status setzen. Ein eventuell vorliegender Kommentar zur Bestellung kann in die Email eingefügt werden.

Die Benachrichtigungs-Emails wird beim nächsten Durchlauf von MailBeez versendet. Um den Zeitversatz zwischen Setzen des Bestell-Status und Versand der Email gering zu halten, empfehlen wir mit Hilfe eines Cronjobs MailBeez z.B. minütlich auszuführen. Der MailBeez Support hilft bei Fragen hierzu.

Anwendungsbeispiele:

- Eine externe Software zur Bestellbearbeitung setzt den Bestellstatus, jedoch ohne eine Benachrichtung zu versenden
- Sie möchten die Standard Bestelltstatus-Email mit einer eigenen Version ersetzen
- Sie möchten Abläufe in Abhängigkeit vom Bestell-Status automatisieren

**Vorlagen Variablen**

 Vorlagen-VariableAusgabe{$status\_date}formatiertes Datum des Bestell-Status{$status\_date\_raw}  
{$ORDER\_STATUS\_DATE}unformatiertes Datum des Bestell-Status{$status\_id}Bestell-Status-ID{$status\_name}  
{$ORDER\_STATUS}Bestell-Status-Name{$comments}Kommentar
V2.3
- added order status name as template variable

V2.2
- added configuration for sender and sender name

V2.1
- supporting multiple notifications per order (for each status one)

V2.0
- initial public version

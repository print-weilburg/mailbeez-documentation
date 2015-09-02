---
# http://learn.getgrav.org/content/headers
title: Shopauskunft
slug: shopauskunft
# menu: Shopauskunft
date: 10-01-2011
published: true
publish_date: 10-01-2011
# unpublish_date: 10-01-2011
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
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/03/sa.png'
    pro: ''
    cert: ''
    price: ''
    title_en: 'Shopauskunft'
    teaser_en: ''
    title_de: 'Shopauskunft'
    teaser_de: 'Kunden automatisch um Bewertungen auf Shopauskunft.de bitten'
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

Bewertungs Email-Modul für Deutschlands größtes Online-Shop-Bewertungsportal.

**Das Qualitäts-Siegel für Kundenvertrauen**  
[![](http://www.shopauskunft.de/res/sa_siegel_rand_180x_20b_5df.jpg)](http://www.shopauskunft.de/retailer_process.html)SHOPAUSKUNFT verhilft Ihrem Shop mittels Kundenbewertungen zu mehr nachhaltigem Kundenvertrauen und dem damit verbundenen Umsatz. **Ihre Vorteile**

- Steigerung der Vertrauenswürdigkeit
- Steigerung der Konversionsrate
- Steigerung des Warenkorbvolumens
- Kundenbindung
- Aktive Nutzung von Beschwerdemanagement
- Wandelung von unzufriedenen zu Wiederholungskäufern
- Nutzung der zufriedenen Kunden als Referenz und somit als Werbung für Ihren Shop
- Analyse der Stärken und Schwächen Ihres Shops aus Sicht der Kunden durch unsere aufbereiteten Daten
- Integration Ihres Shops in Deutschlands größtes Portal für Online-Shop-Bewertungen
- Suchmaschinenoptimierung mittels Verlinkung bei und durch SHOPAUSKUNFT

[![Jetzt Shop registrieren](http://www.shopauskunft.de/res/bttn_jetztshopregistrieren_c5bf.png "Jetzt Shop registrieren")](http://www.shopauskunft.de/about_packages.html)

 

# Konfiguration des Modules:

[![](http://www.mailbeez.com/wp-content/uploads/2011/01/config_shopauskunft-140x300.png "config_shopauskunft")](http://www.mailbeez.com/wp-content/uploads/2011/01/config_shopauskunft.png)

**Aktiviere Shopauskunft Modul**  
 Möchten Sie Ihre Kunden zur Bewertung auf Shopauskunft.de auffordern?  
 Hier legen Sie fest, ob Sie das Module aktiv einsetzen wollen.

**Bestell Status**  
 Eine Bestellung muss diesen gewählten Bestell-Status haben, damit das Modul eine Bewertungsaufforderung an den Kunden verschickt.

Wenn Sie möchten, so können Sie in Ihrem System einen neuen Status z.B. “Shopbewertung OK” einführen und damit kontrollieren, welche Kunden eine Aufforderung zur Bewertung erhalten sollen.

**Anzahl Tage nach Abschluss der Bestellung**  
 Bitte geben Sie die Anzahl der Tage an, die vergangen sind, seit dem die Bestellung auf den gewählten Bestell-Status gesetzt wurde.

Stellen Sie sicher, dass nach Ablauf dieser Zeitraumes die Bestellung auch tatsächlich beim Kunden angekommen ist. Der zeitliche Abstand zwischen Lieferung und Aufforderung der Bewertung sollte aber so kurz wie möglich sein.

**Anzahl der Tage, nach denen eine Bestellung ignoriert wird**  
 Bitte geben Sie die Anzahl der Tage an, nach denen Sie Bestellungen bei der Prüfung ignorieren wollen

Hiermit legen Sie fest, wie “weit in die Vergangenheit” das Modul blicken soll. Wenn MailBeez täglich ausgeführt wird (z.B. automatisch per Cronjob) braucht diese Zahl nur etwas grösser als “Anzahl Tage nach Abschluss der Bestellung” sein.

***TIPP: **Wenn Sie gerade auf Shopauskunft.de gestartet sind, können Sie sehr einfach Ihre Kunden der z.B. letzten 6 Monate zur Bewertung auffordern. So können Sie innerhalb weniger Tage eine – abhängig von der Grösse Ihres Shops – beachtliche Anzahl von Bewertungen einsammeln.  
*

Gehen Sie so vor:

- Stellen Sie den Zeitraum auf z.B. 5 und 180 Tage und führen Sie das Modul aus.  
 Hiermit erhalten die Kunden mit Bestellungsversand in der Zeitspanne von vor 5 Tagen bis 6 Monaten genau EINE Aufforderung für die Bestellung mit der “grössten” Bestellnummer – auch wenn mehrere Bestellung im Zeitraum vorliegen.
- Jetzt den Zeitraum auf z.B. 5 und 10 stellen.  
 Somit wird fortlaufend beim jedem Durchlauf von MailBeez geprüft, ob neue Bestellung mit einem Versanddatum vor 5 bis 10 Tagen vorliegen und ggf. eine Aufforderung verschickt.  
 Voraussetzung: die Bestell-Nummern sind chronologisch – das Modul verschickt nur dann eine neue Aufforderung, falls für den Kunden eine Bestellung mit höherer Bestell-Nummber als beim letzten Aufforderungsversand vorliegt.

Das MailBeez Framework stellt sicher, dass jeder Kunde pro Bestellung nur 1 Email erhält, auch wenn das Modul mehrfach täglich ausgeführt wird.

**Shopauskunft Händler ID**  
 Bitte geben Sie Ihre individuelle Shopauskunft Händler ID ein – Sie erhalten diese ID von Shopauskunft.de

**Optional**  
 Optionale Parameter – wählen Sie, welche optionalen Parameter Sie an Shopauskunft übermitteln wollen:

- KUNDENEMAIL
- USERNAME
- BESTELLDATUM
- LIEFERDATUM
- WARENWERT
- ZAHLUNGSWEISE
- VORNAME
- NACHNAME

**Absender email Adresse**  
 Die Email-Adresse wird als Absender der Aufforderung zur Bewertung verwendet.

**Absender Name**  
 Dieser Name wird als Absender der Aufforderung zur Bewertung verwendet.

**Sortier-Reihenfolge**  
 Sortier-Reihenfolge der Module im MailBeez Admin. Von Niedrig nach Hoch. Hat keine Bedeutung für die Funktion.

**Email Vorlage**  
 Sie können die Email Ihrem Shop Design, Kundenkreis und Bedürfnissen anpassen.

Die Email wird aus einer Rahmen-Vorlage (txt und html), einer Inhalts-Vorlage (txt und html) sowie einer Betreff-Vorlage generiert.  
 Alle Vorlagen sind in Text-Dateien definiert und können leicht mit einem üblichen Editor angepasst werden.

Rahmen-Vorlagen – werden von allen MailBeez Modulen genutzt (falls nicht anders konfiguriert)

- (shop-root)/mailhive/common/templates/email\_html.tpl (html version)
- (shop-root)/mailhive/common/templates/email\_txt.tpl (txt version)

Inhalts-Vorlagen

- (shop-root)/mailhive/mailbeez/shopauskunft/email/body\_html.tpl (html version)
- (shop-root)/mailhive/mailbeez/shopauskunft/email/body\_txt.tpl (txt version)

Betreff-Vorlage

- (shop-root)/mailhive/mailbeez/shopauskunft/email/subject.tpl

Folgend ein Screenshot der Email basierende auf den Standard-Vorlagen:

[![](http://www.mailbeez.com/wp-content/uploads/2011/01/email_shopauskunft-225x300.png "email_shopauskunft")](http://www.mailbeez.com/wp-content/uploads/2011/01/email_shopauskunft.png)

- - - - - -

mit folgenden Premium-Modulen können Shopauskunft Enterprise Partner den Nutzen der Partnerschaft optimieren:

**NEU: [Modul-Pakete im Tarif](https://apps.mailbeez.de) ab 9,99Eur pro Monat**

### [  
![](http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2012/02/icon_64.png)Shopauskunft Integration Suite](http://www.mailbeez.de/dokumentation/configbeez/config_shopauskunft_integration/)

 MailBeez.com, V. 2.0  
  
 LINK\_COMPATIBILITY\_DE

Download: 159 EUR evtl. zzgl MwSt. Ihr Kauf wird sicher durch unseren Partner Avangate abgewickelt  
[Wer ist Avangate](http://www.avangate.com/de/shopper-support/) 

 

[button text](http://localhost/wordpress_mailbeez_EOL/wp-content/plugins/download-monitor/download.php?id=55)



 

 

 ![](http://www.mailbeez.com/wp-content/uploads/2011/09/cert.png)**24 Monate frei Updates! Jetzt kaufen und von zukünftigen Entwicklungen profitieren.**  
Dieses Module erfordert ein personalisiertes Zertifikat, welches für einen Online-Shop gültig ist. Dieses Zertifikat wird zusammen mit den Download Informationen geliefert. Bitte unbedingt die richtige Shop URL eingeben, im Zweifelsfalle bitte VOR der Bestellung [MailBeez kontaktieren](/uber/kontakt/). 

**NEU: [Modul-Pakete im Tarif](https://apps.mailbeez.de) ab 9,99Eur pro Monat**

### [  
![](http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2012/02/icon_641.png)Shopauskunft: Gutschein für Bewertungen](http://www.mailbeez.de/dokumentation/mailbeez/coupon_review_shopauskunft/)

 MailBeez.com, V. 2.0  
  
 LINK\_COMPATIBILITY\_DE

Download: 99 EUR evtl. zzgl MwSt. Ihr Kauf wird sicher durch unseren Partner Avangate abgewickelt  
[Wer ist Avangate](http://www.avangate.com/de/shopper-support/) 

 

[button text](http://localhost/wordpress_mailbeez_EOL/wp-content/plugins/download-monitor/download.php?id=56)



 

 

 ![](http://www.mailbeez.com/wp-content/uploads/2011/09/cert.png)**24 Monate frei Updates! Jetzt kaufen und von zukünftigen Entwicklungen profitieren.**  
Dieses Module erfordert ein personalisiertes Zertifikat, welches für einen Online-Shop gültig ist. Dieses Zertifikat wird zusammen mit den Download Informationen geliefert. Bitte unbedingt die richtige Shop URL eingeben, im Zweifelsfalle bitte VOR der Bestellung [MailBeez kontaktieren](/uber/kontakt/). 

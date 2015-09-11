---
# http://learn.getgrav.org/content/headers
title: Shopauskunft: Gutschein für Bewertungen
slug: coupon_review_shopauskunft
# menu: Shopauskunft: Gutschein für Bewertungen
date: 08-02-2012
published: true
publish_date: 08-02-2012
# unpublish_date: 08-02-2012
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
download:
    code: 'coupon_review_shopauskunft'
    category: [mailbeez]
    compatiblity: [comp_cre,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2012/02/icon_641.png'
    pro: 'pro'
    cert: 'true'
    price: '99 EUR'
    title_en: 'Shopauskunft Review Reward'
    teaser_en: 'Reward customers Shopauskunft Reviews with a discount voucher'
    title_de: 'Shopauskunft: Gutschein f&uuml;r Bewertungen'
    teaser_de: 'Bedanken Sie sich f&uuml;r Bewertungen auf Shopauskunft - mit einem Gutschein'
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

Dieses Modul erfordert die [Mailbeez Shopauskunft Integration Suite ](http://www.mailbeez.de/dokumentation/configbeez/config_shopauskunft_integration/ "Mailbeez Shopauskunft Integration Suite").

**Bedanken Sie sich beim Kunden für das Abgeben von Bewertungen auf Shopauskunft**

Bewertungen auf Shopauskunft.de sind für Online-Shops (nahezu) Gold wert! Statistiken zeigen, dass eine grosse Anzahl von Bewertungen den Umsatz steigern.

**Personaliserte Gutscheine schützen vor ungewünschter Verbreitung**

Der Versand von allgemein gültigen Gutscheinen birgt das Risiko, dass diese einen ungewünschten Viralen Effekt bekommen. Um dies zu vermeiden, generiert MailBeez automatisch personalisierte Gutscheine für jeden Empfänger der Kampagne – Sie können im Gutschein System bei der Konfiguration der Gutschein-Vorlage selber wählen, wie oft dieser eingesetzt werden darf.

**Professionelle Vorlagen**

per Maus-Klick kann aus einer Reihe von professionellen Vorlagen gewählt werden:

Wie alle MailBeez Kampagnen Module, so wird auch bei diesem Module der Inhalt der Email mit Hilfe von Vorlagen generiert – diese sind einfach anpassbar, so dass das Design Ihres Online-Shops auch in den Emails angewendet werden kann.

## Installation

Wie bei fast allen MailBeez Modulen, so ist die Installation mit dem FTP Transfer der Modul-Dateien und anschliessender Aktivierung im Admin erledigt.

Um das Gutschein-System des Online-Shops mit dem Module zu verknüpfen, sind lediglich folgende Schritte erforderlich:

**Schritt 1: Gutschein-Vorlagen für den Einsatz in MailBeez anlegen.**

Um Gutscheinvorlagen in MailBeez Modulen auswählen zu können, müssen diese zunächst in der Gutschein Administration angelegt werden:

- **Gutschein Code**- hier ist Namenskonvention: der Gutschein-Code muss mit “template\_” beginnen, als z.B. “template\_bewertung1″
- **Gutschein Name** – Hier den Namen des Gutscheines nach eigener Wahl eingeen
- **Gutschein Datum Felder** – Die Eingaben hier sind nicht relevant – MailBeez erzeugt diese Daten beim Generieren eines Gutscheines
- **Anzahl Verwendungen** – nach eigenem Wunsch, z.B. “1″ konfigurieren

die Gutschein-Vorlage wie gewohnt speichern.  
**Schritt 2: Das MailBeez Modul konfigurieren**

Nachdem jetzt also eine Gutschein Vorlage im System ist, wieder in die MailBeez Administration wechseln. Dort in der Modulkonfiguration die jetzt sichtbare Gutschein Vorlage aus der Drop-Down Liste wählen und die Modulkonfiguration speichern.

MailBeez in den “Simulation” Mode bringen und das Modul ausführen – es werde die zur Konfiguration passenden Emails generiert.

Die erzeugten Simulations Gutscheine tragen die Kennung [SIM] – dies ermöglicht die einfache Unterscheidung von Simulations Gutscheinen und “echten” Gutscheinen.

Mit der integrierten Funktion “Simulations Gutscheine löschen” können diese bequem wieder aus dem System entfernt werden.

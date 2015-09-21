---
# http://learn.getgrav.org/content/headers
title: Gutschein: Wiederbestellen
slug: reorder_advanced
routes:
    aliases:
        - /dokumentation/mailbeez/coupon_reorder
        - /dokumentation/mailbeez/gutschein-wiederbestellen
# menu: Gutschein: Wiederbestellen
date: 15-08-2011
published: true
publish_date: 15-08-2011
# unpublish_date: 15-08-2011
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
    tag: [pro,coupon]
module:
    code: 'reorder_advanced'
    category: [mailbeez]
    compatiblity: [comp_cre,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/10/coupon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '99 EUR'
    title_en: 'Reorder Advanced'
    teaser_en: 'Say thanks to your customers, and send them a reorder coupon towards their next purchase'
    title_de: 'Gutschein für die nächste Bestellung'
    teaser_de: 'Bedanken Sie sich beim Kunden für den Einkauf mit einem Gutschein für die nächste Bestellung'
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

**Bedanken Sie sich beim Kunden für den Einkauf mit einem Gutschein für die nächste Bestellung – Häufig kommt die dann schneller als erwartet!**

Gelegentliche Aufmerksamkeiten in Form eines Gutscheines ist eine schöne Art und Weise sich für den Kauf zu bedanken – besonders für Online Shops im harten Wettbewerb wo jede Bestellung zählt. Das MailBeez “Gutschein für die nächste Bestellung” gibt Ihnen die Möglichkeit nicht nur zu wählen, in welchem Zeitraum nach der Bestellung der Kunden kontaktiert wird, sondern auch ob dies schon gleich nach der ersten, zweiten dritten oder erst ab der 4. Bestellung geschehen soll – dies vermeidet, Kunden frühzeitig Gutscheine in die Hand zu geben, welche dann unnötigerweise den Gewinn reduzieren.

**Personaliserte Gutschein schützen vor ungewünschtem Einsatz**

Der Versand von allgemein gültige Gutschein birgt das Risiko, dass diese einen ungewünschten Viralen Effekt bekommen. Um diese Falle zu vermeiden, generiert MailBeez automatisch personalisierte Gutscheine für jeden Empfänger der Kampagne – Sie können im Gutschein System bei der Konfiguration der Gutschein-Vorlage selber wählen, wie oft dieser eingesetzt werden darf.

**Intelligente Aktivierung**

Es wäre nicht sehr intelligent Gutscheine ein Kunden zu verschicken, der Bestellung aufgrund Verzögerungen noch nicht in den Versand gegangen ist. Um diese Situation zu vermeiden, arbeitet das Modul nur auf Bestellungen einen bestimmten Bestell-Status haben – es können beliebig vielen Bestellstatus aktiviert werden.

**Professionelle Vorlagen**

per Maus-Klick kann aus einer Reihe von professionellen Vorlagen gewählt werden:

**Responsive Emails mit MailBeez?**  
![](http://www.mailbeez.com/images/responsive.png) ([Was sind responsive Emails?](/dokumentation/responsive-emails/)) In Kombination mit der [Responsive Vorlagen Verwaltung](/dokumentation/mailbeez/config_tmplmngr) können Sie eine responsive Email Vorlage wählen und nach Ihren Wünschen anpassen.  
Die gezeigten Design-Vorlagen sind noch nicht responsive, wir werden dies baldmöglichst anpassen (Damit MailBeez responsive Emails versenden kann, ist auf jeden Fall die [Responsive Vorlagen Verwaltung](/dokumentation/mailbeez/config_tmplmngr)) erforderlich. ****


Wie alle MailBeez Kampagnen Module, so wird auch bei diesem Module der Inhalt der Email mit Hilfe von Vorlagen generiert – diese sind einfach anpassbar, so dass das Design Ihres Online-Shops auch in den Emails angewendet werden kann.

## Installation

Wie bei fast allen MailBeez Modulen, so ist die Installation mit dem FTP Transfer der Modul-Dateien und anschliessender Aktivierung im Admin erledigt.

Um das Gutschein-System des Online-Shops mit dem Module zu verknüpfen, sind lediglich folgende Schritte erforderlich:

**Schritt 1: Gutschein-Vorlagen für den Einsatz in MailBeez anlegen.**

Um Gutscheinvorlagen in MailBeez Modulen auswählen zu können, müssen diese zunächst in der Gutschein Administration angelegt werden:

- **Gutschein Code**- hier ist Namenskonvention: der Gutschein-Code muss mit “template\_” beginnen, als z.B. “template\_wiederbestellen1″
- **Gutschein Name** – Hier den Namen des Gutscheines nach eigener Wahl eingeen
- **Gutschein Datum Felder** – Die Eingaben hier sind nicht relevant – MailBeez erzeugt diese Daten beim Generieren eines Gutscheines
- **Anzahl Verwendungen** – nach eigenem Wunsch, z.B. “1″ konfigurieren

die Gutschein-Vorlage wie gewohnt speichern.  
**Schritt 2: Das MailBeez Modul konfigurieren**

Nachdem jetzt also eine Gutschein Vorlage im System ist, wieder in die MailBeez Administration wechseln. Dort in der Modulkonfiguration die jetzt sichtbare Gutschein Vorlage aus der Drop-Down Liste wählen und die Modulkonfiguration speichern.

MailBeez in den “Simulation” Mode bringen und das Modul ausführen – es werde die zur Konfiguration passenden Emails generiert.

Die erzeugten Simulations Gutscheine tragen die Kennung [SIM] – dies ermöglicht die einfache Unterscheidung von Simulations Gutscheinen und “echten” Gutscheinen.

Mit der integrierten Funktion “Simulations Gutscheine löschen” können diese bequem wieder aus dem System entfernt werden.

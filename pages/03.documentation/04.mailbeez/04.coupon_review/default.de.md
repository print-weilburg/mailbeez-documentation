---
# http://learn.getgrav.org/content/headers
title: Gutschein für Bewertungen
slug: coupon_review
routes:
    aliases:
        - /dokumentation/mailbeez/gutschein-fur-bewertungen
date: 21-10-2011
published: true
publish_date: 21-10-2011
# unpublish_date: 21-10-2011
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
    code: 'coupon_review'
    category: [mailbeez]
    compatiblity: [comp_cre,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/10/coupon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '99 EUR'
    title_en: 'Review Reward Coupon'
    teaser_en: 'Say thanks to your customers for giving a review, and send them an automated email with a personalized coupon'
    title_de: 'Gutschein für Bewertungen'
    teaser_de: 'Bedanken Sie sich beim Kunden für das Abgeben von Produktbewertungen'
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

**Bedanken Sie sich beim Kunden für das Abgeben von Produktbewertungen**

Produktbewertungen sind für Online-Shops (nahezu) Gold wert! Statistiken zeigen, dass eine grosse Anzahl von Bewertungen den Umsatz steigern.

**Personaliserte Gutscheine schützen vor ungewünschter Verbreitung**

Der Versand von allgemein gültigen Gutscheinen birgt das Risiko, dass diese einen ungewünschten Viralen Effekt bekommen. Um dies zu vermeiden, generiert MailBeez automatisch personalisierte Gutscheine für jeden Empfänger der Kampagne – Sie können im Gutschein System bei der Konfiguration der Gutschein-Vorlage selber wählen, wie oft dieser eingesetzt werden darf.

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

---
# http://learn.getgrav.org/content/headers
title: Newsletter Profi
slug: newsletter
# menu: Newsletter Profi
date: 11-08-2011
published: true
publish_date: 11-08-2011
# unpublish_date: 11-08-2011
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
download:
    code: 'mb_newsletter'
    category: [mailbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/10/icon_32.png'
    pro: 'pro'
    cert: 'true'
    price: '179 EUR'
    title_en: 'Newsletter Advanced'
    teaser_en: 'The Newsletter Module for MailBeez, with Segmentation, Coupons and more'
    title_de: 'Newsletter Profi'
    teaser_de: 'Das Newsletter Module für MailBeez, mit Segmentierung, Gutscheinen und mehr'
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

Das MailBeez Newsletter Profi Modul ist eine grundlegende Neu-Entwicklung und ein neu-gedachter Ansatz eines mit dem Shop-System voll integrierten Newsletter Systems.

**Responsive Newsletter**  
In Kombination mit der Responsive Vorlagen Verwaltung wird das Newsletter Profi Modul um responsive Funktionen erweitert, so dass mit dem visuellem Editor repsonsive Emails erstellt werden können, mehr dazu auf [Responsive Emails mit MailBeez](http://www.mailbeez.com/dokumentation/responsive-emails/)

Die Standard-Newsletter Funktion von osCommerce, Gambio, ModifiedShop & Zencart ist rudimentär und zeigt in der Praxis eine Vielzahl an Schwächen.

Mit dem MailBeez Newsletter Profi-Modul wird diese Lücke geschlossen und Shopbetreiber können nun endlich professionelle Newsletter direkt aus dem Shopsystem versenden. Da das MailBeez Newsletter Profi Modul direkt in das Shopsystem eingebettet ist, müssen keine Daten exportiert oder importiert werden. Es kann sofort ein Newsletter an z.B. alle Kunden mit einem aktiven Newsletter-Abo versendet werden.

Das Erstellen von Newslettern wird mit dem MailBeez Newsletter Profi Modul denkbar einfach gemacht: der Visuelle Editor ermöglicht das Verfassen von professionellen Newslettern, welche bestmöglich in den wichtigsten Email-Programmen dargestellt werden. In Kombination mit der [Responsive Vorlagen-Verwaltung](http://www.mailbeez.com/dokumentation/mailbeez/config_tmplmngr) (auch im [MailBeez Profi Paket](http://www.mailbeez.com/download/mailbeez-essential-pack/) enthalten) können auch mobil-freundliche Newsletter erstellt werden, welche optimal auf z.B. iPhones dargestellt werden.



### Beispiele:

Die freie Kombinierbarkeit der Segmentierungsregeln eröffnen eine Vielzahl von Möglichkeiten, zielgerichtete Newsletter zu versenden:

**Einmalige Weihnachtsgeschäfts-Kunden vom letzten Jahr**

- Segmentierung: 1 Kauf im Zeitraum 1. Oktober 2012 bis 31. Dezember 2012
- Gutschein: 10%, gültig 14 Tage

**Feiertags-Newsletter an alle Kunden**

- Vorprogrammierung des Versende-Datums
- keine weitere Segmentierung

**Willkommens-Newsletter Serie**

- Segmentierung: Kunde seit mindestens / höchstens Tagen

**Produkt-Warnhinweis / Rückruf an alle betroffenen Kunden**

- Segmentierung: Kunden, welche Produkt X gekauft habe + Umgehung des Newsletter-Abo

**Upsell / Cross-Sell**

- Segmentierung: Kunden, welche Produkt A aber nicht Produkt B gekauft haben
- Gutschein: freie Versandkosten innerhalb von 7 Tagen

### Funktionen

**Listen**

- Anlegen, bearbeiten und Löschen von Empfängerlisten
- unbegrenzte Anzahl an Empfängerlisten
- Segmentierung der Listen
- Testen von Segmentierungen

**Segmentierungs-Möglichkeiten**

- Geografisch: Land, Bundesland, Plz
- Kunde: Geschlecht, Kunde seit mindestens / höchstens Tagen, Kunden-Gruppe: erfordert [Kundengruppen-Filter](http://www.mailbeez.com/dokumentation/mailbeez/filter_check_group)
- Produkte: gekaufte Produkte (Whitelist & Blacklist)
- Kategorien: gekaufte Produkte (Whitelist & Blacklist)
- Bestellungen: max. Anzahl Bestellungen, letzte Bestellung nach Datum & vor Datum
- Konfiguration von Ländern, für die ein Newsletter Abo nicht erforderlich ist

**Kampagnen**

- Anlegen, bearbeiten und Löschen von Kampagnen
- unbegrenzte Anzahl an Kampagnen
- eine Kampagne kann unbegrenzt viele Newsletter enthalten
- Zuweisen einer Standard-Liste (kann auf Newsletter ebene überschrieben werden)

**Newsletter**

- Aktiv von Datum bis Datum
- Auswahl eine Liste (oder Kampagnen-Standard)
- Auswahl einer Gutschein-Vorlage

**Gutschein**

- basiert auf dem MailBeez Gutschein-Generator
- Anlegen von Gutschein-Vorlagen mit allen zur Verfügung stehenden Optionen
- automatische Generierung von personalisierten Gutscheinen
- Gültigkeit in Tagen und Gutschein-Code-Länge konfigurierbar

**Statistiken**

- Volle Integration mit MailBeez Analytics bzw. Google Analytics
- Auswertung von Öffnen, Click, Bestellung

### Versendeprozess

Newsletter können entweder manuell oder automatisiert versendet werden. Pro Aufruf der Versende-Funktion wird die als "Stapel Grösse" konfigurierte Anzahl an Emails versendet. Somit ist die Versende-Funktion entsprechend oft aufzurufen, bis die gesamte Anzahl an Emails versendet worden ist.

**Konfigurations-Beispiel für automatisches Versenden:**

Einrichtung eines Cronjobs (z.B. alle 5 Minuten), welches ausschliesslich anstehende Newsletter versendet:

 
    wget -O - -q -t 1 <cronurl>\&module=mb_newsletter


Stapel-Grösse:

 
    100 Emails


Einfache Drosselung (Zusatzmodul):

 
    3600 Emails pro Stunde


Pro Aufruf des Versendeprozesses werden also 100 Emails versendet, etwa 1 Email pro Sekunde. Der Cronjob startet den Versendeprozess alle 5 Minuten (12x pro Stunde), somit werden 1200 Emails pro Stunde versendet.

In Abhängigkeit des zur Verfügung stehenden Mail-Servers kann der Mailversand beschleunigt werden oder muss ggf. weiter gedrosselt werden.

Durch die Drosselung und die Begrenzung der Anzahl mit Hilfe der Stapel-Grösse können Limits von Hostern bzw. den Email-Server eingehalten werden sowie das Risiko von Spam-Ratings reduziert werden.

### Empfohlene Module

Für einen reibungslosen Einsatz des MailBeez Newsletter Profi Module werden folgende Erweiterungen des MailBeez Systems empfohlen - alle MailBeez Module profitieren hiervon:

- [Einfache Drosselung](http://www.mailbeez.com/dokumentation/mailbeez/filter_do_throttling_simple) (auch im [MailBeez Profi Paket](http://www.mailbeez.com/download/mailbeez-essential-pack/) enthalten)
- [Bouncehive Rückläufer-Verarbeitung](http://www.mailbeez.com/dokumentation/mailbeez/config_bouncehive_advanced)
- [Kundengruppen-Filter](http://www.mailbeez.com/dokumentation/mailbeez/filter_check_group)

Um responsive Newsletter erstellen und versenden zu können, ist die MailBeez Responsive Vorlagen-Verwaltung erforderlich:

- [Responsive Vorlagen-Verwaltung](http://www.mailbeez.com/dokumentation/mailbeez/config_tmplmngr) (auch im [MailBeez Profi Paket](http://www.mailbeez.com/download/mailbeez-essential-pack/) enthalten)

### geplante Weiterentwicklungen

- weitere Email-Vorlagen
- weitere Inhaltsbereichs-Vorlagen
- MailBeez Template-Tags per Button einfügen (aktuell nur für firstname & lastname)
- automatische Erstellung von Produktdarstellungen
- personalisierte Inhalte
- "Interessenten Funktion": Besucher können sich für den Newsletter eintragen. Wenn aus den Besucher Kunden werden, wird dies natürlich erkannt. Somit können leicht verschiedene Newsletter für Interessenten und Kunden versendet werden.

## haben Sie Ideen?

![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/icons/slategrey/Megaphone.png) Nur her damit! MailBeez wird für Shopbetreiber entwickelt und Ihre Ideen sind wichtig!

[ Meine Ideen zum Newsletter Modul](http://helpdesk.mailbeez.com/509106-MailBeez)
V2.32
- fixed bug in segmentation engine

V2.31
- fixed bug in segmentation engine

V2.3
- fixed bug in segmentation engine
- added "min order count" as rule

V2.26
- fixed bug in segmentation engine

V2.25
- fixed an issue with prospects management

V2.2
- improved segmentation engine
- added categories filter
- improved products filter (blacklist now across orders)

V2.1
- added zipcode filter
- added support for customer profiling engine

V2.0
- added extendable segmentation engine

V1.4
- added support for modified-shop 1.06 / newsletter_recipients table

V1.3
- fixed issue with groupfilter
- improve responsive button (outlook)

V1.2
- minor fixes

V1.1
- minor changes

V1.0
- initial public release
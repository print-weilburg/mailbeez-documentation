---
# http://learn.getgrav.org/content/headers
title: Bitte zur Shopbewertungen
slug: shoprating
# menu: Bitte zur Shopbewertungen
date: 13-05-2014
published: true
publish_date: 13-05-2014
# unpublish_date: 13-05-2014
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

Dieses Modul zur Bewertungsaufforderung ist bereits im Modul [Shopbewertungen](http://www.mailbeez.com/dokumentation/configbeez/config_shopvoting/) enthalten.

Mit dem Shopbewertungs-Modul können Kunden eine Bewertung des Shops abgeben, diese Bewertungen sind dann in der Administrations zu bearbeiten und das Ergebnis kann in der Storefront angezeigt werden.

Mit diesem Modul können Shop-Betreiber ihre Kunden automatische zur Abgabe einer Bewertung auffordern.

Für den ernsthaften Einsatz des Shopbewertungs-Modules empfiehlt sich das MailBeez Modul "[Shopbewertung Profi](http://www.mailbeez.com/dokumentation/mailbeez/shoprating_advanced/ "Shopbewertung Profi")", welches bis zu doppelt so viele Bewertungen gibt und es erlaubt, Shopbewertungen in anderen MailBeez Emails (z.B. [Kundenrückgewinnung Profi](http://www.mailbeez.com/dokumentation/mailbeez/winback_advanced/) ) anzuzeigen

## Shopbewertung Einfach / [Shopbewertung Profi - mit Autologin](http://www.mailbeez.de/dokumentation/mailbeez/shoprating_advanced/ "Shopbewertung Profi")

  [Edit](http://localhost/wordpress_mailbeez_EOL/wp-admin/tools.php?page=wp-table-reloaded&action=edit&table_id=7 "Edit") EinfachProfiKommentar Kunden automatisch um eine Bewertung bittenPRO\_YESPRO\_YESDie Shopbewertungen kommen leider nicht von alleine, also besser nachhelfen Mehrere Bestell-Status möglichPRO\_NOPRO\_YESKonfiguration auf welche Bestellstatus das Module reagiert Automatischer LoginPRO\_NOPRO\_YESDer Kunde kann sofort seine Bewertung abgeben Bestell-Nummer vor-ausfüllenPRO\_NOPRO\_YESDie Bestell-Nr wird bereits vor-ausgefüllt (konfigurierbar) Stammkunden erkennenPRO\_NOPRO\_YESUm Stammkunden nicht bei jeder Bestellung zu kontaktieren, kann eine Zeitspanne zwischen Bewertungen definiert werden, z.B. "nur alle 120 Tage um Bewertung bitten" Mehrstufige ErinnerungPRO\_NOPRO\_YESFreundliches Nachfragen kann Wunder - oder besser: doppelte so viele Bewertungen bringen (konfiguierbar bis zu 3x, erfordert Bestell-Nr) Professionelle VorlagenPRO\_NOPRO\_YESWähle aus einer Liste professioneller Vorlagen Liste der bestellten ProduktePRO\_NOPRO\_YESZur Erinnerung wird eine Liste der bestellten Produkte eingefügt (konfigurierbar) Test-ProduktePRO\_NOPRO\_YESSchon beim Versand einer Test-Email wird eine Liste angezeigt Shopbewertungen in allen oder ausgewählten MailBeez Emails anzeigenPRO\_NOPRO\_YESÜber eine Template-Variable können z.B. 3 zufällige Bewertungen mit mindestens 4 Sternen in alle (Haupttemplate) oder ausgewählte MailBeez Emails eingefügt werden. Quer-PrüfungPRO\_NOPRO\_YESPrüft ob der Kunden schon vom Standard-Modul kontaktiert wurde oder dies geblockt hat. White Label EmailsPRO\_NOPRO\_YESCopyright freie EmailsMehr Bewertungen erhalten Sie mit [Shopbewertung Profi - mit Autologin](http://www.mailbeez.com/dokumentation/mailbeez/shoprating_advanced/ "Shopbewertung Profi")

 

## Sinnvolle Erweiterungen:

[MailBeez automatisch Ausführen](http://www.mailbeez.com/documentation/configbeez/config_cron_simple/ "Run MailBeez Automatically") damit werden Kunden voll automatisch aufgefordert

[Kundengruppen Filter](http://www.mailbeez.com/documentation/filterbeez/filter_check_group/ "Customer Group Filter") bestimmt, welche Kundengruppen eine Aufforderung erhalten soll

[Newsletter Abo-Check](http://www.mailbeez.com/documentation/filterbeez/filter_check_newslettersubscriber/ "Newsletter Subscribers only") nur Kunden mit Newsletter-Abo kontaktieren

[Musterbasierte Blacklist](http://www.mailbeez.com/documentation/filterbeez/filter_check_pattern_blacklist/ "Pattern Blacklist") hilfreich, wenn z.B. Kunden über marketplace.amazon.de bestellen, diese dürfen nicht direkt kontaktiert werden

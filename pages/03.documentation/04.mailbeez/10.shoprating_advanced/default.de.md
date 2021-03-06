---
# http://learn.getgrav.org/content/headers
title: Bitte zur Shopbewertung Profi
slug: shoprating_advanced
# menu: Bitte zur Shopbewertung Profi
date: 13-05-2014
published: true
publish_date: 13-05-2014
# unpublish_date: 13-05-2014
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
module:
    code: 'shoprating_advanced'
    category: [mailbeez]
    compatiblity: [comp_osc,comp_cre,comp_digi,comp_zencart,comp_xtc,comp_gambio]
    thumbnail: 'http://www.mailbeez.com/wp-content/uploads/downloads/thumbnails/2011/10/icon_322.png'
    pro: 'pro'
    cert: 'true'
    price: '99 EUR'
    title_en: 'Shopvoting Advanced'
    teaser_en: 'The advanced module for the professional application of the "shopvoting" addon'
    title_de: 'Shopbewertung Profi'
    teaser_de: 'Das Profi-Modul für den ernsthaften Einsatz des Modules "Shopbewertung"'
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

Dieses Modul ist für den professionellen Einsatz der kostenfreien Erweiterung [Shopbewertungen](http://www.mailbeez.com/dokumentation/configbeez/config_shopvoting/) entwickelt worden.

Mit dem Shopbewertungs-Modul können Kunden eine Bewertung des Shops abgeben, diese Bewertungen sind dann in der Administrations zu bearbeiten und das Ergebnis kann in der Storefront angezeigt werden.

Mit diesem Modul können Shop-Betreiber ihre Kunden automatische zur Abgabe einer Bewertung auffordern.

## viele Profi-Funktionen

Im Vergleich zur kostenlosen Version bietet das Shopbewertung Profi Module eine Reihe von Funktionalitäten, die mehr Bewertungen ergeben wie z.B. Auto-Login und Stammkunden-Erkennung.

Zudem können die Bewertungen auch in anderen Modulen (z.B. zur Kundenrückgewinnung) vorteilhaft integriert werden.

[![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/lib/scripts/timthumb/thumb.php?src=http://www.mailbeez.com/images/de_shoprating_advanced_integration.png&w=250&h=350&zc=1&q=100 "real time customer ratings in MailBeez Emails")](http://www.mailbeez.com/images/de_shoprating_advanced_integration.png "real time customer ratings in MailBeez Emails")![](http://localhost/wordpress_mailbeez_EOL/wp-content/themes/awake/images/shortcodes/image_shadow.png)

## Shopbewertung Einfach / [Shopbewertung Profi - mit Autologin](/dokumentation/mailbeez/shoprating_advanced/ "Shopbewertung Profi")

  [Edit](http://localhost/wordpress_mailbeez_EOL/wp-admin/tools.php?page=wp-table-reloaded&action=edit&table_id=7 "Edit") EinfachProfiKommentar Kunden automatisch um eine Bewertung bittenPRO\_YESPRO\_YESDie Shopbewertungen kommen leider nicht von alleine, also besser nachhelfen Mehrere Bestell-Status möglichPRO\_NOPRO\_YESKonfiguration auf welche Bestellstatus das Module reagiert Automatischer LoginPRO\_NOPRO\_YESDer Kunde kann sofort seine Bewertung abgeben Bestell-Nummer vor-ausfüllenPRO\_NOPRO\_YESDie Bestell-Nr wird bereits vor-ausgefüllt (konfigurierbar) Stammkunden erkennenPRO\_NOPRO\_YESUm Stammkunden nicht bei jeder Bestellung zu kontaktieren, kann eine Zeitspanne zwischen Bewertungen definiert werden, z.B. "nur alle 120 Tage um Bewertung bitten" Mehrstufige ErinnerungPRO\_NOPRO\_YESFreundliches Nachfragen kann Wunder - oder besser: doppelte so viele Bewertungen bringen (konfiguierbar bis zu 3x, erfordert Bestell-Nr) Professionelle VorlagenPRO\_NOPRO\_YESWähle aus einer Liste professioneller Vorlagen Liste der bestellten ProduktePRO\_NOPRO\_YESZur Erinnerung wird eine Liste der bestellten Produkte eingefügt (konfigurierbar) Test-ProduktePRO\_NOPRO\_YESSchon beim Versand einer Test-Email wird eine Liste angezeigt Shopbewertungen in allen oder ausgewählten MailBeez Emails anzeigenPRO\_NOPRO\_YESÜber eine Template-Variable können z.B. 3 zufällige Bewertungen mit mindestens 4 Sternen in alle (Haupttemplate) oder ausgewählte MailBeez Emails eingefügt werden. Quer-PrüfungPRO\_NOPRO\_YESPrüft ob der Kunden schon vom Standard-Modul kontaktiert wurde oder dies geblockt hat. White Label EmailsPRO\_NOPRO\_YESCopyright freie Emails## Sinnvolle Erweiterungen:

[MailBeez automatisch Ausführen](/documentation/configbeez/config_cron_simple/ "Run MailBeez Automatically") damit werden Kunden voll automatisch aufgefordert

[Kundengruppen Filter](/documentation/filterbeez/filter_check_group/ "Customer Group Filter") bestimmt, welche Kundengruppen eine Aufforderung erhalten soll

[Musterbasierte Blacklist](/documentation/filterbeez/filter_check_pattern_blacklist/ "Pattern Blacklist") hilfreich, wenn z.B. Kunden über marketplace.amazon.de bestellen, diese dürfen nicht direkt kontaktiert werden
Version 3.1
- autologin improvements

Version 3.0
- support for shopvoting module

Version 2.4
- general improvements
- updated config_social
Version 2.31
- compatiblity with MailBeez V2.7
Version 2.3
- fixed bug with new certificate handling
---
title: Simulation
slug: config_simulation
date: 28-09-2015
published: true
template: docs
visible: true
summary:
    enabled: true
    format: short
    size: 128
taxonomy:
    migration_status: done
    category: [docs]
    tag: [core]
author:
    name: admin
metadata:
    author: admin
---

MailBeez unterscheidet grundsätzlich zwischen den Betriebsarten:

1. **Simulation**
2. **Production**


### Simulation [SIM]

der Simulations-Modus ist gedacht, um - schwer zu erraten - die Funktion des Systemes anhand von Simulationen zu testen.
Im Simulations-Modus arbeiten alle Module wie im Produktions-Modus, ABER: alle Emails werden nur an die hier hinterlegte Email-Adresse versendet und nicht an die Kunden!
Zur Kennzeichnung von Simulations-Emails wird die Kennung [SIM] z.B. im Email-Betreff und in Gutschein-Code verwendet.

Beim Neu-Start einer Simulation werden alle Simulations-Daten gelöscht.


### Production

Wenn Sie mit den Ergebnissen der Simulations-Durchläufen zufrieden sind, können Sie beruhigt in die Betriebsart "Production" wechseln. Beim Ausführen der Module werden dann die Emails generiert und an die Kunden versendet.
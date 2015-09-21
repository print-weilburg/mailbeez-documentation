---
title: Ordner Struktur
slug: ordner-struktur
taxonomy:
    category: docs
---

Mailbeez ist natlos in Ihr vorhandenes Shopsystem integrierbar. Das Hauptverzeichnis von Mailbeez ist `mailhive. Es befindet sich in Ihrem Shop Hauptverzeichnis (Root). Bei Shopversionen, welche Mailbeez bereits vorinstalliert haben, befindet sich das Mailbeez-Hauptverzeichnis in folgendem Ordner: 
- **Gambio 2.3+**: `ext/mailhive` 
- **Modified-Shop 2.+**: `includes/external/mailhive`

Im Ordner `mailhive` befinden sich folgende Unter-Ordner:

```bash
/common
/common/template_c
/configbeez
/dashboardbeez
/filterbeez
/gui
/images
/includes
/install
/mailbeez
/reportbeez
```

Hier eine kurze Erklärung wofür diese einzelnen Ordner stehen:

### /common

Der Ordner `common` beinhaltet  gemeinsam genutzte Dateien des Grund-Systemes

### /common/template_c

Innerhalb des Ordners `common` befindet sich der Ordner `template_c`, in dem temporär erstellte Dateien gespeichert werden, wie z.B. Smarty Cache Dateien, Anwendungs-Cache Dateien usw.

### /configbeez

Der `configbeez` Ordner beinhaltet die Konfigurationsmodule, diese erscheinen im Register "Konfiguration" (sofern sie nicht absichtlich verborgen wurden).

### /dashboardbeez

Der `dashboardbeez` Ordner beinhaltet die Dashboard Module, diese erscheinen (sofern sie nicht absichtlich verborgen oder nicht installiert wurden) auf dem MailBeez Dashboard (Mailbeez Startseite)


### /filterbeez

Im Ordner `filterbeez` befinden sich die einzelnen Filter- & Hilfs-Module, diese erscheinen (sofern sie nicht absichtlich verborgen oder nicht installiert wurden) im Register "Filter- & Hilfsmodul".

### /gui (deprecated)

Der Ordner `gui` ist veraltet - Er beinhaltet Dateien, um die Abmelde-Seite darzustellen, wenn User auf Abmelde-Links klicken


### /images

Der Ordner `images` kann benutzt werden, um eigene Bilddateien zu speichern, wie z.B. das E-Mail Header Logo


### /includes

Der Ordner `includes` beinhaltet die Erweiterungen, um die Mailbeez Funktionen innerhalb des Shop- oder Adminbereiches zu integrieren.


### /install

Der Ordner `install` beinhaltet Dateien, die nur bei Shopsystemen basierend auf xt:commerce verwendet werden.


### /mailbeez

Der Ordner `mailbeez` beinhaltet die einzelnen MailBeez Module, diese erscheinen (sofern sie nicht absichtlich verborgen oder nicht installiert wurden) im Register "MailBeez Module".


### /reportbeez

Der Ordner `reportbeez` beinhaltet die Berichts Module, diese erscheinen (sofern sie nicht absichtlich verborgen oder nicht installiert wurden) im Register "Berichte"


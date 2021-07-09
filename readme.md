# PET-Template

## Deutsch
Dieses Repository enthält eine schlichte, von mir erstellte Vorlage um Penetrationstestberichte für die Vorlesung *PET (Penetration Testing)* an der [Hochschule Mannheim](https://www.hs-mannheim.de/) in *LaTeX* schreiben zu können.

Enthalten sind:
- Ein Paket (`pentest-report.sty`), welches die grundlegenden Einstellungen vornimmt und ermöglicht, Verwundbarkeitstabellen per `vulntable`-Befehl zu erstellen
    - `vulntable` nimmt als Argumente jeweils die Inhalte der 5 Spalten der entsprechenden Tabelle entgegen
- Ein Blanko-Bericht (`report.tex`) der im Wesentlichen auf die Überschriften der im Zuge der Vorlesung zur Verfügung gestellten Word-Vorlage reduziert wurde
- Eine gekürzte Fassung eines von mir verfassten Berichts (`example_report.tex`), die eine beispielhafte Anwendung der Vorlage zeigt
    - Der Beispiel-Bericht ist zur einfacheren Einsicht auch als PDF im `doc`-Ordner enthalten
- Eine Konfiguration für [Visual Studio Code](https://code.visualstudio.com/) (`settings.json`), welche die [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)-Erweiterung vorkonfiguriert

Zum aktuellen Zeitpunkt ist die Vorlage für Berichte in deutscher Sprache konfiguriert.


**HINWEIS:**
**Das Repository ist für die Verwendung mit [Git LFS](https://git-lfs.github.com/) konfiguriert.**
**Falls nötig, kann dies über die `.gitattributes` Datei geändert werden.**

## English
This repository contains a simple template for creating penetration test reports in *LaTeX*.
It is intended to be used by students who are attending the *PET (Penetration Testing)* lecture at the [Hochschule Mannheim](https://www.hs-mannheim.de/).

This repository contains:
- A package (`pentest-report.sty`), which configures the most important settings and provides the `vulntable` command to simplify the creation of vulnerability table
    - `vulntable` takes the content of each of the five table rows as arguments
- An empty report (`report.tex`), shortened to basically only contain the headings
- An abridged version of a report of mine (`example_report.tex`), to illustrate the use of the template
    - This exemplary report is also available as PDF
- A configuration file for [Visual Studio Code](https://code.visualstudio.com/) (`settings.json`) which provides a basic configuration for the [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension

Please be aware, that the template currently assumes that the report will be written in German.


**NOTE:**
**The repository is configured to use [Git LFS](https://git-lfs.github.com/).**
**If needed, it can be configured by editing the `.gitattributes` file.**

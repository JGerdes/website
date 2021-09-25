---
title: Mensaport
date: 2015-06-21T11:00:00+02:00
summary: Eine komfortable und simple App für die Mensa der Hochschule Bremen am Airport.
tags: [mensa,hsb,android,material-design]
header:
    image: /assets/images/mensaport/header.png
    scrim: 0.3
actions:
    - label: Zeige im PlayStore
      action: https://play.google.com/store/apps/details?id=com.jonasgerdes.mensaport.mensaport
---

Mensaport ist eine App für Android, welche die Gerichte der kommenden 14 Tage anzeigt, die in der Mensa der Hochschule Bremen am Standort in der Flughafenallee angeboten werden.  Es gibt zwar bereits einige alternative Apps, die dies tun, allerdings sind diese meist nicht speziell für die Hochschule Bremen gedacht und sind designtechnisch nicht wirklich ansprechend.

Daher habe ich, auch um meine Erfahrung mit der Umsetzung des Material Designs von Google unter Android zu erweitern, eine eigene App entwickelt. Sehr minimalistisch werden in der Hauptansicht die Gerichte für den heutigen Tag oder, z.B. am Wochenende, die des nächsten Werktages angezeigt. Neben einer Beschreibung werden Informationen über den Preis für Studenten und Mitarbeiter der Hochschule Bremen sowie ein Icon zum Teilen des Gerichts per Mail, SMS oder anderen Messenger angezeigt. Üben einen Drawer auf der linken Seite kann zwischen den Tagen gewechselt werden.

<img src="/assets/images/mensaport/screen1.png" alt=" Übersicht der Gerichte eines Tages" class="left">
<img src="/assets/images/mensaport/screen2.png" alt=" Im Drawer kann ein Tag ausgewählt werden" class="left">
## Datenherkunft
<p>Nach kurzer Suche und Analyse der <a href="http://www.stw-bremen.de/de/essen-trinken/mensa-am-airport" 
		target="_blank">Website des Studentenwerk Bremens</a> konnte ich leider keine öffentliche API finden, unter der die aktuellen Informationen der Mensa erreichbar sind. Deswegen habe ich einen eigenen Server eingerichtet, der die besagte Website crawlt, die Daten mit einem [DOM-Parser](https://github.com/paquettg/php-html-parser) parst und der App die Gerichte im JSON-Format verfügbar macht.</p>
## Todos
<ul><li>Caching der Daten für Offlinenutzung</li><li>Speichern von Favoriten</li><li>serverseitiges Caches pro Tag</li><li>eventuell persistentes Speichern der Gerichte in einer eigenen Datenbank, um Statistiken oder Bewertungen zu ermöglichen</li></ul>
## Download
Die Anwendung steht im [GooglePlay Store](https://play.google.com/store/apps/details?id=com.jonasgerdes.mensaport.mensaport) zur Verfügung und ist für Geräte mit Android 4.1 und höher kompatibel.


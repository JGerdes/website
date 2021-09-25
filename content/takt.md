---
title: Takt
date: 2016-04-24T13:09:00+02:00
summary: Ein BPM-Detektor für die Pebble Time Round. Ermittelt die Geschwindigkeit (Schläge pro Minute) von Liedern oder dient als Metronom.
tags: [c,music,bpm,smartwatch,pebble]
header:
    image: /assets/images/takt/header.jpg
    scrim: 0.2
actions:
    - label: Zeige im PebbleStore
      action: https://apps.getpebble.com/en_US/application/5714065395235f65eb000019
    - label: Auf GitHub
      action: https://github.com/JGerdes/Takt
---

Ob Musikant oder DJ, Takt gibt Besitzern der Smartwatch [Pebble Time Round](https://www.pebble.com/pebble-time-round-smartwatch-features) die Möglichkeit, die Geschwindigkeit von Liedern in Schlägen pro Minute (BPM) zu ermitteln. Daneben kann Takt außerdem als Metronom verwendet werden: Einmal eine Geschwindigkeit ermittelt oder eingestellt, blinkt der Bildschirm der Smartwatch im Takt.

<img src="/assets/images/takt/watchface.gif" class="pebble right" alt=" Der Bildschirm blinkt im Takt mit 125 BPM" class="left">
Als weiteres Features ist das Displays der Uhr mit zwei Kreisen umrandet, die, auf Basis eines Viervierteltakts, die aktuelle Position im Takt und in 4 Takten visualisiert.

<h2 class="no-clear">Steuerung</h2>
Über den mittleren Knopf der Pebble Time Round kann die Geschwindigkeit (BPM) ermittelt werden. Dazu muss dieser regelmäßig bei jedem Viertelschlag gedrückt werden. Ein Mittel aus den letzten zehn Schlägen wird dann in Schläge pro Minute umgerechnet und angezeigt.

Durch Drücken des oberen Knopfes kann die Position im Takt/in 4 Takten zurückgesetzt werden.

## Download
Die Watch-App kann als [Pebble Watch-App](https://apps.getpebble.com/en_US/application/5714065395235f65eb000019) heruntergeladen und installiert werden.

Der Sourcecode von Takt steht auf [GitHub](https://github.com/JGerdes/Takt) zur Verfügung.

<p class="source">Header-Bild von [Puk Khantho](https://unsplash.com/@puk_khantho)


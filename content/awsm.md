---
title: AWSM - TowerDefence
date: 2015-08-01T10:10:00+02:00
summary: Kleines TowerDefence-Spiel für Windows, das als Abschlussprojekt für den Kurs Game Programming Patterns entwickelt wurde.
short_summary: TowerDefence-Spiel in C#.
tags: [spiel,windows,c#,sfml,cinema4d,jonapps]
header:
    image: /assets/images/awsm/header.png
    scrim: 0.2
actions:
    - label: Download
      action: /download/awsm.zip
---

AWSM ist ein kleines Tower-Defence-Spiel. Es ist in meinem sechsten Semester in einer Gruppenarbeit mit [Jonathan Wiemers](http://jonathanwiemers.com/) (siehe auch [JonApps](http://jonapps.com/)) für den Kurs „Game-Programming-Patterns“ entstanden. In diesem haben wir über das Semester verteilt immer wieder kleinere Spiele in C# und der [SFML.NET](http://www.sfml-dev.org/) Bibliothek programmiert, aus denen wir dann essentielle Pattern und Codeteile extrahiert und als eigenen kleine Library genutzt haben. Mit mehr Spielen wurde diese Bibliothek immer größer, bis am Ende fast ein eigenes Game-Framework entstanden ist.

Während des letzten Spiels sollte vor allem Wert darauf gelegt werden, dass die Logik des Codes von Assets getrennt werden. Das heißt, Grafiken, Musik, Farbinformationen und Eigenschaften/Verhalten der Gegner im Spiel sollten aus eigenen Dateien zur Laufzeit gelesen werden, sodass diese modifiziert werden können, ohne den Code für das Spiel neu als ausführbare Anwendung kompilieren zu müssen.

Dies ist uns mit AWSM relativ gut gelungen. Neue Level können bequem durch das Erstellen eines neuen Ordners kreiert werden. Dieser beinhaltet entsprechende Dateien zur Beschreibung des Levels und der Gegner (Farben, Stärke, Geschwindigkeit etc.), die alle im JSON-Format sind und zu Beginn des Spiels automatisch ausgelesen werden. Dadurch ist eine einfache Erweiterung des Spiels möglich.

## Spielprinzip
Der Spieler hat eine Auswahl von Türmen, die er für Energie kaufen und bauen kann. Dies Türme können in einen gewissen Radius mit einer gewissen Frequenz schießen. Mit ihnen muss der Spieler verhindern, dass die Gegner es schaffen, auf ihrem definierten Weg das Ende des Levels zu erreichen. Sollte dies eine gewisse Anzahl an Gegner gelingen, verliert der Spieler und muss/kann das Level erneut spielen. Abgeschossene Gegner verlieren Energie, die der Spieler bekommt und somit neue Türme bauen kann. Die Gegner erscheinen in Wellen, die der Spieler nacheinander auslösen kann. Sind alle Wellen vorüber, hat der Spieler gewonnen.

{{<video src="/assets/videos/awsm_game_play.mp4" poster="/assets/videos/awsm-poster.png">}}
## Steuerung
#### Überall
_ESCAPE_: Beenden des Spiels

#### Menü
_Pfeiltasten_ oder _W-A-S-D_: Auswahl
_ENTER_: Auswahl bestätigen

#### Spiel
_Pfeiltasten_ oder _W-A-S-D_ oder Maus an den Rand bewegen: Verschieben der Ansicht
    	_1, 2, 3, ..._: Auswahl eines Turmes
    	_Klicken_: Ausgewählten Turm an Mausposition bauen
    	_N_ oder _ENTER_: Nächste Welle starten (Wenn vorherige vorbei ist)
    	_Q_: Alle Türme abwählen
    	_M_: Zurück ins Hauptmenü

## Soundtrack
Da wir zum Ende des Semesters ein möglichst komplettes Spiel abliefern wollten, brauchten wir noch Musik. Ohne Audio ist ein Spiel nur ein halbes Spiel! Für jedes Level sowie für das Hauptmenü habe ich daher je ein kurzes Lied produziert.

<div class="track"><div class="track__info">01 - Main Theme - AWSM OST</div><audio src="awsm/ost/01_main_theme_128.mp3" data-cover="assets/images/awsm/ost/cover.png" data-wave="/assets/images/awsm/ost/track1.svg" data-wave-played="/assets/images/awsm/ost/track1_played.svg" controls></audio></div>
<div class="track"><div class="track__info">02 - The Icosahedron - AWSM OST</div><audio src="awsm/ost/02_the_icosahedron_128.mp3" data-cover="assets/images/awsm/ost/cover.png" data-wave="assets/images/awsm/ost/track2.svg" data-wave-played="/assets/images/awsm/ost/track2_played.svg" controls></audio></div>
<div class="track"><div class="track__info">03 - Polygon Beach - AWSM OST</div><audio src="awsm/ost/03_polygon_beach_128.mp3" data-cover="assets/images/awsm/ost/cover.png" data-wave="assets/images/awsm/ost/track3.svg" data-wave-played="/assets/images/awsm/ost/track3_played.svg" controls></audio></div>
<div class="track"><div class="track__info">04 - Route N8 - AWSM OST</div><audio src="awsm/ost/04_route_n8_128.mp3" data-cover="assets/images/awsm/ost/cover.png" data-wave="assets/images/awsm/ost/track4.svg" data-wave-played="/assets/images/awsm/ost/track4_played.svg" controls></audio></div>

Alle Tracks können in voller Qualität als [Album heruntergelanden](/download/awsm_ost.zip) werden.

## Download
Das Spiel ist kompatibel mit Windows und kann als [Standalone-Anwendung heruntergeladen](/download/awsm.zip) werden. Zum Spielen muss das zip-Archiv entpackt und _AWSM.exe_ ausgeführt werden.


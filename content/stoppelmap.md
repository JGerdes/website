---
title: StoppelMap
date: 2015-08-12T19:32:00+02:00
summary: Inoffizielle Android-App für den Stoppelmarkt in Vechta
short_summary: Android-App für den Stoppelmarkt in Vechta.
tags: [stoppelmarkt,google-maps,android,material-design]
header:
    image: /assets/images/stoppelmap/header.png
    scrim: 0.2
actions:
    - label: Zeige im PlayStore
      action: https://play.google.com/store/apps/details?id=com.jonasgerdes.stoppelmap
---

StoppelMap ist eine App für Android, die eine interaktive Karte des Stoppelmarkts in Vechta zeigt. Dabei wird die Map-Funktion der Google Play Services genutzt. Die normale Kartenansicht ist deaktiviert und die Karte des Stoppelmarkts wird aus vom Gerät geladenen Grafikkacheln dargestellt. So kann die App auch ohne eine Internetverbindung genutzt werden. Das ist sinnvoll, da auf dem Gelände des Marktes durch die große Anzahl an Leuten der mobile Internetempfang oft nicht ausreichend ist, um Kartenmaterial zu laden.

Die App beinhaltet dazu noch eine Suchfunktion, die verschiedene Arten von Eingaben verarbeiten kann. So kann direkt nach dem Namen eines Festzeltes oder eines Fahrgeschäftes, oder aber auch nach einem Stichwort wie „WC“, „Bier“, „Pommes“ oder „Parkplatz“ gesucht werden.

{{< figure class="phone" src="/assets/images/stoppelmap/screen1.png" alt="In der Sucheleiste der App wurde \"sch\" eingeben. Vorschläge, die diese Buchstabenkombination enthalten (wie z.B. \"Piratenrutsche\") werden darunter angezeigt." caption="Die Suche zeigt passende Vorschläge während der Eingabe.">}}

{{< figure class="phone" src="/assets/images/stoppelmap/screen2.png" alt="Auf der Karte werden an entsprechenden Stellen Toiletten mit dem Label \"WC\" hervorgehoben." caption="Ergebnisse der Suche nach „WC“ werden auf der Karte angezeigt.">}}

Aufgrund der Klausurenphase und Projektabgaben innerhalb meines Studiums konnte ich die StoppelMap leider nicht so früh anfangen, wie ich gerne gewollt hätte. So wurden einige Stände erst kurz vorher, teilweise sogar erst während der Markt bereits im Gange war, eingefügt. Da das Grundgerüst sowie ein Skript zum automatischen Zerschneiden einer großen Grafik in die einzelnen Kacheln für die verschiendenen Zoomstufen für GoogleMaps ja jetzt bereits fertig ist, hoffe ich, für das nächste Jahr früher beginnen und noch allerhand weitere Funktionen implementieren zu können.

## Download
Die Anwendung steht im [GooglePlay Store](https://play.google.com/store/apps/details?id=com.jonasgerdes.stoppelmap) zur Verfügung und ist für Geräte mit Android 2.3 und höher kompatibel.


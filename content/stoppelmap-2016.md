---
title: StoppelMap 2016
date: 2016-08-10T22:27:00+02:00
summary: Eine komplett überarbeitete Version der inoffiziellen Android-App für den Stoppelmarkt in Vechta.
short_summary: Neue Version der StoppelMap für 2016.
tags: [stoppelmarkt,google-maps,android,material-design]
header:
    image: /assets/images/stoppelmap-2016/header.png
    scrim: 0.2
actions:
    - label: Laden von Google Play
      action: https://play.google.com/store/apps/details?id=com.jonasgerdes.stoppelmap
---

StoppelMap ist eine App für Android, die eine interaktive Karte des [Stoppelmarkts in Vechta](http://www.stoppelmarkt.de/) zeigt. Als Nachfolger der [im letzten Jahr erstmals veröffentlichten Version](/StoppelMap) habe ich in diesem Jahr die App von Grund auf neu entwickelt und um einige neue Features erweitert. Weitere Information zur StoppelMap können auch auf der [Website der App](https://stoppelmap.de) nachgelesen werden.

## Karte
{{< figure src="/assets/images/stoppelmap-2016/screen_bottomsheet.png" alt="StoppelMap-Screen mit Informationen zum Zelt 'Kühlings Niedersachsenhalle'" caption="Klicken auf ein Zelt oder Fahrgeschäft zeigt weitere Informationen">}}

Die Grundfunktion, eine interaktive Karte, ist im Groben unverändert geblieben. Auch dieses Jahr besteht diese aus einer GoogleMaps-Karte, die allerdings kein Kartenmaterial von Google lädt, sondern von der App bereitgestellte Kacheln, auf denen die Straßen des Marktes sowie, in unterschiedlichen Farben gekennzeichnet, die Zelte, Fahrgeschäfte und Stände des Stoppelmarkts zu sehen sind. Zusätzlich sind die Namen der Stände usw. an der jeweiligen Stelle verzeichnet. Die Karte kann - wie von GoogleMaps gewohnt - gezoomt, und verschoben werden. Je nach Zoomstufe werden die Namen der Stände dynamisch ausgeblendet, damit die Karte stets übersichtlich bleibt.

Als neue Funktionen auf der Karte können dieses Jahr erstmals die einzelnen Bereiche der Stände, Zelte usw. angetippt werden. Dadurch fährt im unterem Bereich des Bildschirms eine kompakte Übersicht ein, die den Namen, ein Bild sowie Icons für Angebote des angetippten Elements anzeigt. Über eine Schaltfläche "mehr" wird dann eine Ansicht mit weiteren, zum Zelt/Fahrgeschäft/Stand passenden Informationen wie der nächsten Veranstaltung, einer Beschreibung usw. geöffnet.

## Suche
{{< figure src="/assets/images/stoppelmap-2016/screen_search.png" alt="StoppelMap-Screen mit Suche" caption="Die Suchfunktion findet Fahrgeschäfte, Zelte, Stände und mehr">}}

Die Grundidee der App bestand darin, möglichst schnell ein Zelt, Fahrgeschäft oder Stand zu finden, wenn man danach sucht. Daher bietet StoppelMap eine Suchfunktion, die auch sehr spezielle Suchanfragen findet. So kann direkt der Name, wie beispielsweise _Amtmannsbult_ eingegeben werden. Auch alternative Namen wie z.B. _Luttener Zelt_ für das Festzelt _Pickers_ sind hierbei nutzbar. Dies hilft vor allem erstmaligen Besuchern des Marktes, die entsprechende Alternativnamen noch nicht kennen.

Fahrgeschäfte werden häufig nach Funktion oder Art betitelt, anstatt des offiziellen Namens. Daher bietet die Suchfunktion auch die Möglichkeit, z.B. über die Begriffe _Wasserbahn_, _Wildwasserbahn_ oder auch _Baumstammkanal_ das Fahrgeschäft _Piratenfluss_ zu finden.

Um die Vielzahl der Stände ordentlich zu durchsuchen, unterstützt die Suche die Eingabe von dort angebotenen Speisen oder Getränken. Eine Suche nach _Eis_ findet alle Stände, an denen es Eis gibt. Suche nach _Bier_ findet sowohl Stände als auch Festzelte, in denen Bier ausgeschenkt wird.

{{< figure src="/assets/images/stoppelmap-2016/screen_tags.png" alt="StoppelMap-Screen mit Toiletten" caption="Wo ist die nächste Toilette in Deiner Nähe?">}}

Als wichtiger Use-Case deckt die Suche auch das Finden einer Toilette in der Nähe ab. Gibt man einen Begriff in der Suchleiste ein, wird direkt ab dem ersten Buchstaben eine Liste mit Ergebnissen anzeigt. Diese Ergebnisliste enthält gemischte Ergebnisse: Einerseits direkte Einzelergebnisse, die beispielsweise bei der Suche nach einem speziellem Festzelt sinnvoll sind. Andererseits zusammengefasste Ergebnisse, wie zum Stichwort _WC_. Wählt der Nutzer ein solches Stichwortergebnis, werden auf der Karte die zutreffenden Stände etc. angezeigt, die sich in seiner Nähe befinden. Einzelergebnisse werden direkt auf der Karte zentriert und herangezoomt.

## Programmplan
{{< figure src="/assets/images/stoppelmap-2016/screen_events.png" alt="Stoppelmarkt - Programmübersicht" caption="Der Programmplan gibt einen Überblick über die Veranstaltungen">}}

Als weitere neue Funktion beinhaltet StoppelMap dieses Jahr einen Programmplan. Dieser umfasst sowohl das offizielle Programm wie Festumzug, Viehmarkt und Feuerwerk, aber auch die Veranstaltungen der einzelnen Festzelte.

Für jeden der sechs Veranstaltungstage des Stoppelmarkts gibt es einen Tab, der eine chronologische Liste alle Events an diesem  Tag öffnet. Zu jedem Event werden allgemeine Informationen und je nach Eventtyp Musikgenre, Künstler oder andere beteiligte Personen, Location sowie Start- und Endzeit angezeigt. Wenn zu der Veranstaltung ein Event auf facebook existiert, wird dieses verlinkt.

Auch für den Programmplan gibt es eine Suchfunktion. Hier kann nach allen verfügbaren Informationen wie Musikgenre, Künstler, Ort oder direkt der Name der Veranstaltung gesucht werden.

## Busfahrpläne
{{< figure src="/assets/images/stoppelmap-2016/screen_bus.png" alt="Stoppelmarkt - Busfahrplan" caption="Über die Busfahrpläne kann die nächste Haltestelle und Abfahrt zum Markt gefunden werden.">}}

Viele Besucher erreichen den Stoppelmarkt über die verkehrenden Shuttle-Busse. Um komfortabel die nächte Haltestelle und Abfahrtszeit zu finden, verfügt die StoppelMap über einen intelligenten Busfahrplan. Dieser zeigt alle Buslinien, geordnet nach Abstand zur nächsten Haltestelle von der aktuellen Position des Nutzers aus, an. Direkt angezeigt wird außerdem die nächste Abfahrtszeit. Antippen einer Linie öffnet die Detailansicht, in der alle sich auf der Strecke des Linie befindlichen Haltestellen aufgelistet sind und je die drei nächsten Abfahrtszeiten angezeigt werden. Durch Antippen einer Haltestelle gelangt man in eine dritte Ansicht. Hier bietet ein Wochenplan Übersicht über alle kommenden und vergangenen Abfahrten an dieser Haltestelle sowie den Preis für eine Fahrt zum Markt von dieser aus. Des Weiteren kann über eine Option direkt eine Navigationsapp gestartet werden, die dann zur Haltestelle navigiert.

## Teilen
{{< figure src="/assets/images/stoppelmap-2016/screen_share.png" alt="StoppelMap - Teilfunktion" caption="Stände, Zelte usw. können per Messenger mit anderen geteilt werden.">}}

Um im Vorraus anderen Leuten ein Fahrgeschäft zu zeigen oder auf dem Markt mitzuteilen, in welchem Festzelt man sich gerade befindet, können alle Stände, Zelte und Fahrgeschäfte über einen Share-Button in Messengern wie WhatsApp oder Telegram, sozialen Netzwerken oder auch per Mail geteilt werden. Unterstützt die entsprechend gewählte App das [Open-Graph-Protokoll](http://ogp.me/), wird sogar als Vorschau in der App der Name sowie ein Bild der geteilten Attraktion angezeigt. Andere Nutzer der StoppelMap können dann den geteilten Link öffnen und werden direkt auf die Karte geleitet, die auf den geteilten Stand, das geteilte Zelt etc. zentriert ist.

## Download
Die Anwendung steht im [GooglePlay Store](https://play.google.com/store/apps/details?id=com.jonasgerdes.stoppelmap) zur Verfügung und ist für Geräte mit Android 4.1 und höher kompatibel.



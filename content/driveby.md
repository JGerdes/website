---
title: Driveby
date: 2021-06-12T10:18:09+02:00
draft: false
summary: Android-App, die interessante Informationen zu nahegelegenden Orten erzählt. Entwickelt beim jacobsHack! 2016.
tags: [tts,gps,android,wikipedia,hackstrong,hackathon]
header:
    image: /images/driveby/header.jpg
    scrim: 0.5
actions:
    - label: Auf Devpost
      action: https://devpost.com/software/driveby-pfbslc
    - label: Auf GitHub
      action: https://github.com/28hacks/driveby
---

DriveBy ist eine App für Android, die dem Nutzer unterwegs wissenswerte Informationen zu Städten, Sehenswürdigkeiten, Landschaften etc. vorliest.

Dabei wurde der Fokus darauf gelegt, dass die App "handsfree also ohne großartige Eingabe des Nutzer funktioniert. Einmal gestartet läuft DriveBy im Hintergrund. Nun wird, sobald beispielsweise eine interessante Stadt in der Nähe ist, eine Heads-Up-Benachrichtigung angezeigt und ein Fakt zu dieser vorgelesen. Das funktioniert sogar mit ausgeschaltetem Bildschirm.

Falls der Nutzer die bereits gehörten Informationen noch einmal nachlesen möchte, hat er die Möglichkeit, dies über die History-Funktion der App zu tun. Dort werden in chronologischer Reihenfolge alle angefahrenden Orte aufgelistet. Antippen eines Eintrags leitet auf die mobile Seite des jeweiligen Eintrag von Wikipedia weiter.

!["History-Ansicht](/images/driveby/screen_history.png)
!["Heads-Up-Benachrichtigung](/images/driveby/screen_notification.png)

## Entwicklung
Entwickelt wurde DriveBy innerhalb von 24 Stunden im Rahmen des Hackerthons [jacobsHack!](//jacobshack.com) 2016 von [Stefan Oberdörfer](//github.com/stefanoberdoerfer) und mir.
Dabei waren wir beide an der App an sich tätig, da kein Backend benötigt wurde. Anhand der GPS-Position des Nutzers werden die Daten über die offene API von Wikipedia geladen und dann in einzelne Sätze zerschnitten, die dann über die vom Android-Framework bereitgestellte Text-to-Speech-Funktionalität vorgelesen werden.
## Auszeichnungen
DriveBy wurde von der Jury des [jacobsHack!](//jacobshack.com) zum Sieger in der Kategorie _Most disruptive project_ ernannt.
Mehr Informationen dazu auch auf [Devpost](//devpost.com/software/driveby-pfbslc). Quelltext auf [GithHub](//github.com/28hacks/driveby)

[#hackstrong](//twitter.com/search?f=tweets&vertical=default&q=%23hackstrong&src=typd)</p>


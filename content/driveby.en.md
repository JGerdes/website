---
title: Driveby
date: 2016-10-18T22:27:00+02:00
draft: false
summary: Android app telling you interesting facts about near by places. Developed at jacobsHack! 2016.
short_summary: Android app telling interesting facts about near by places.
tags: [tts,gps,android,wikipedia,hackstrong,hackathon]
header:
    image: /assets/images/driveby/header.jpg
    scrim: 0.5
actions:
    - label: On Devpost
      action: https://devpost.com/software/driveby-pfbslc
    - label: On GitHub
      action: https://github.com/28hacks/driveby
---

DrivyBy is an app for Android which reads out interesing facts about near by cities, sights and landscapes on the go.

The unique feature of the app is it's "handsfree" usages - meaning that it (in most parts) can be used without users interacting with it. Once started, DriveBy will run in the background. When an interesting place is passed by, a head up notification is shown and a fact is read out. This even works with the screen turned off.

{{< figure class="phone" src="/assets/images/driveby/screen_notification.png" alt="Heads up notification of DriveBy" caption="A heads up notification shows the name of the place that a fact was read out about.">}}

In case users want to read already heard facts again, they have the opportunity to do this with the history feature of the app, where all passed by places are shown chronologically. A tap on a history entry navigates to the article of that place on Wikipedia.

{{< figure class="phone" src="/assets/images/driveby/screen_history.png" alt="History feature" caption="The history feature shows already visited places.">}}

## Development
DriveBy was developed during 24 hours at [jacobsHack!](//jacobshack.com) 2016 by [Stefan Oberdörfer](//github.com/stefanoberdoerfer) and me. As we didn't need a backend, both of us were working on the app itself. By passing the phone's GPS location to the open API of Wikipedia, articles of near by places can be fetched. Those are then cut into single sentences and read out by the text to speech functionality provided by the Android framework itself.

## Awards
The jury of [jacobsHack!](//jacobshack.com) awarded DriveBy the winner in the category _Most disruptive project_. See [Devpost](//devpost.com/software/driveby-pfbslc) for more information.

The source code of the projects is available on [GithHub](//github.com/28hacks/driveby).

[#hackstrong](//twitter.com/search?f=tweets&vertical=default&q=%23hackstrong&src=typd)</p>


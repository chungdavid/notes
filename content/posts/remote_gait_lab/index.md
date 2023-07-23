---
title: "Project: Remote gait analysis for children with Equinus Gait"
date: 2023-07-13
# weight: 1
tags: ["project"]
author: "David Chung"
description: "A device that remotely monitors gait in children with Equinus Gait."
canonicalURL: "https://davidchung.me/notes/remote_gait_lab" # url of post
searchHidden: false
showToc: true
hideSummary: true
cover:
    image: "lateral.jpg" # image path/url
    alt: "Lateral view of the remote gait monitoring device" # alt text
    caption: "Lateral view of the device on foot" # display caption under cover
    relative: true # when using page bundles set this to true
    hidden: true # only hide on current single page


draft: false
TocOpen: false
hidemeta: false
comments: false
disableHLJS: true # to disable highlightjs
#disableShare: true #false
disableHLJS: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
editPost:
    URL: "https://github.com/chungdavid/notes/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
## The Project
### Description
A device intended to be operated by parents/guardians of children with cerebral palsy. The device measures the child's ankle joint angle during the gait cycle and outputs a graph for a clinician to analyze. The idea is to perform measurements periodically so the clinician can monitor changes in the child's gait over time. This device can be used to evaluate treatment outcomes.

### Components
- ESP32-PICO-D4
- 2x Adafruit BNO055
- 2x Force Sensitive Resistor

![Medial view of device on foot](medial.jpg)
![Lateral view of device foot](lateral.jpg)
![View of the bottom of the foot with device on](bottom.jpg)
![Output graph from device](graph.png)
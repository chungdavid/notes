---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
# weight: 1
tags: ["tag1","tag2"]
author: "David Chung"
description: "Description of note."
canonicalURL: "https://davidchung.me/notes/<insert here>" # url of post
searchHidden: false
showToc: true
hideSummary: false
cover:
    image: "<img url>" # image path/url
    alt: "img alt text" # alt text
    caption: "img caption" # display caption under cover
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

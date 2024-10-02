---
date: '{{ .Date }}' # date in which the content is created - defaults to "today"
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
draft: false # set to "true" if you want to hide the content 
authors: "" # set authors
venue: ""
image: ""
link: ""
direct_link: true
---

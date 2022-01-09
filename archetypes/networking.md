---
title: "{{ replace .Name "-" " " | title }}"
postdate: {{ dateFormat "January 02, 2006" .Date }}
image: ""
description: ""
alt: ""
weight: ""
author: {{ .Site.Params.author }}
categorylink: /categories/networking-and-communication
categories: ["Networking and Communication"]
type: posts
wordcount: false
mathjax: true
draft: false
---

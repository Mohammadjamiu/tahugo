---
title: "{{ replace .Name "-" " " | title }}"
postdate: {{ dateFormat "January 02, 2006" .Date }}
image: ""
description: ""
alt: ""
weight: ""
author: {{ .Site.Params.author }}
categorylink: /categories/electronics
categories: ["Electronics"]
type: posts
wordcount: false
draft: false
---

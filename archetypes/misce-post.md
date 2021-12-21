---
title: "{{ replace .Name "-" " " | title }}"
postdate: {{ dateFormat "January 02, 2006" .Date }}
image: ""
description: ""
alt: ""
weight: ""
author: {{ .Site.Params.author }}
categorylink: /categories/productivity-and-guides
categories: ["Productivity and guides"]
type: posts
wordcount: false
mathjax: true
draft: false
---

---
title: "{{ replace .Name "-" " " | title }}"
postdate: {{ dateFormat "January 02, 2006" .Date }}
image: ""
description: ""
alt: ""
weight: ""
author: {{ .Site.Params.author }}
categorylink: /categories/maths-and-fun
categories: ["Maths and Fun"]
type: posts
mathjax: true
wordcount: false
draft: false
---

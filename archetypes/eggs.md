---
title: {{ replace .Name "-" " " | title }}
date: {{ .Date }}
draft: false
category: ["eggs"]
tags:
---

# Recipe

- See image

-----

# Original Scanned Image

![](/eggs/{{ .Name }}.png)
---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
tags: ["{{ .tags }}"]
writer: "{{author-login}}"
---
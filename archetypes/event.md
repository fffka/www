---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ dateFormat "2006-01-02" .Date }}
rank: 1
eventDateStart: {{ dateFormat "2006-01-02" .Date }}T23:59:59+02:00
eventDateEnd: {{ dateFormat "2006-01-02" .Date }}T23:59:59+02:00
eventTime: "-"
eventPlace: "-"
summary: ""
---

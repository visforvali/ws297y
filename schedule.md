---
layout: page
title: 🕰️ Weekly Schedule
description: The weekly event schedule.
nav_exclude: false
nav_order: 6
---

# Weekly Schedule 🕰️ 

Most office hours are held in person in 


the Halıcıoğlu Data Science Institute. Office hours held remotely will have zoom links. 

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
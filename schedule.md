---
layout: page
title: 📅 Weekly Schedule
description: The weekly event schedule.
nav_exclude: false
nav_order: 
---

# Weekly Schedule 📅

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
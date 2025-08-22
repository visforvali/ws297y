---
layout: page
title: 🕰️ Weekly Schedule
description: The weekly event schedule.
nav_exclude: false
nav_order: 6
---

# Course Structure 🍎

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
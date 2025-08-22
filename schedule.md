---
layout: page
title: 🕰️ Weekly Schedule
description: The weekly event schedule.
nav_exclude: false
---

# Course Structure 🍎

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
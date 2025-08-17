---
layout: page
title: 🍎 Course Structure
description: The weekly event schedule.
nav_exclude: false
nav_order: 
---

# Course Structure 🍎

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
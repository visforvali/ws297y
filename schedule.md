---
layout: home
title: 🏠 Home
description: The weekly event schedule.
nav_order: 5
---

# Creative Writing for Social Justice: Feminist, Queer, & Trans Perspectives

## WS 297Y, Fall 2025 at Pace University 👋🏾

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

---
layout: page
title: 🕰️ Weekly Schedule
description: The weekly event schedule.
nav_exclude: false
nav_order: 6
---

# Weekly Schedule 🕰️ 

{: .warning }
> You must contact me at least 1 week in advance to schedule a chat outside of my standard coffee chat times. 

The schedule below approximates the "shape" of each week of this class (check the [📅Calendar](https://visforvali.github.io/ws297y/){:target="_blank"} for exceptions to this workflow and detailed descriptions of what we'll do).

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
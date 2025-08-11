---
layout: home
title: /:house:/ Home
description: Listing of course modules and topics.
permalink: /:path/
nav_order: 1
seo:
  type: Course
  name: WS 297Y
---

# Creative Writing for Social Justice: Feminist, Queer, & Trans Perspectives

## WS 297Y at Pace University 👋🏾

: **FALL 2025**{: .label .label-purple } : **TUE, THU 12:15PM - 1:40PM**{: .label .label-purple } : **ONLINE SYNC**{: .label .label-purple }



## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}


{% for module in site.modules %}
{{ module }}
{% endfor %}

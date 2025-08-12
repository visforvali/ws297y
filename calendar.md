---
layout: page
title: 🏠 Home
description: Listing of course modules and topics.
nav_order: 1
permalink: /:path/
seo:
  type: Course
  name: WS 297Y
---

# Creative Writing for Social Justice
<p class="fs-6 fw-300">WS 297Y at Pace University 👋🏾</p>


<small>**Fall 2025**{: .label .label-purple } **Tue, Thu 12:15PM - 1:40PM**{: .label .label-purple } **Online Sync**{: .label .label-purple }</small>


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{: .warning }
> I reserve 5 hrs/wk for by-appointment coffee chats on Discord. This semester, I'm available on Tuesdays from 2:00PM-5:00PM and Wednesdays from 12:00PM-2:00PM. You can book a 5, 10, or 20 min chat with me and choose to use voice-and-video or voice-only (ideal for commutes and workplace breaks). Book early and often! 

> If these times don't work for your schedule, DM me to arrange an alternate time. 

{: .important }
> I respond to async messages — messages in Discord's text channels, direct messages (DMs) on Discord, and Pace emails — within 24 hrs during the week. Anything I get over the weekend, I'll respond to on Mon (you *might* catch me online over the weekend, but don't count on it). 

> For a quicker response to questions outside of class, please ask on Discord #💻classroom or #🔢team (you can @ me to flag my attention).

{% for module in site.modules %}
{{ module }}
{% endfor %}
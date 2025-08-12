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
WS 297Y at Pace University 👋🏾

**Fall 2025**{: .label .label-lavender } **Tue, Thu 12:15PM - 1:40PM**{: .label .label-lavender } **Online Sync**{: .label .label-lavender }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{: .important }
> I reserve 5 hrs/wk for by-appointment coffee chats on Discord on Tue 2:00PM-5:00PM and Wed 12:00PM-2:00PM. You can book a 5, 10, or 20 min chat by clicking the above button. Book early and often! 
> If these times don't work for your schedule, DM me for other times!

{: .important }
> I respond to async communications (DMs and emails) within 48 hrs during the week and to emails received over the weekend on Mon. For lengthy, conversational Q&As, DMs are usually better (as I can often do a sync DM chat no matter where I am or if I'm at my computer).

{% for module in site.modules %}
{{ module }}
{% endfor %}
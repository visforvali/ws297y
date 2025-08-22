---
layout: page
title: 🗓️ Home
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
> I reserve 5 hrs/wk for by-appointment coffee chats on Discord. You can book a 🕐5, 🕐10, or 🕧20 min chat with me over voice-and-video or voice-only (ideal for commutes and work breaks), to talk about any aspect of your classwork, college, life, etc. Book early and often! 
>
> And don't worry if these times don't work for your schedule! Just DM me to arrange an alternate time. You must contact me **at least 1 week in advance** to schedule a chat outside of my standard coffee chat times. 

{: .important }
> I respond to async messages (in in Discord's text channels and DMs, and Pace emails &mdash; within 48 hrs during the week. Anything I get over the weekend, I'll respond to on Mon (I *might* reply sooner, but don't count on it). 
>
> For a quicker response to questions or project help, ask in #classroom or #team on Discord. Please note that I deprioritize questions about course material/logistics that are explained in the course syllabus+ and/or this website, or have already been asked and answered on Discord and added to the [FAQs](/faqs.md) on this site.

{% for module in site.modules %}
{{ module }}
{% endfor %}
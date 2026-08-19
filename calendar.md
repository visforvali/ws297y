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


<small>**Fall 2025**{: .label .label-blue-custom } **Tue, Thu 12:15PM - 1:40PM**{: .label .label-blue-custom } **Online Sync**{: .label .label-blue-custom } **Discord**{: .label .label-blue-custom }</small>


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{: .warning }
> I reserve 5 hrs/wk for by-appointment coffee chats on Discord. You can book a <a href="https://zcal.co/drmani/coffee-chat" target="_blank">🕐10</a>, <a href="https://zcal.co/drmani/coffee-chat?duration=15" target="_blank">🕐15</a>, or <a href="https://zcal.co/drmani/coffee-chat?duration=20" target="_blank">🕧20</a> min chat with me over voice-and-video or voice-only (ideal for commutes and work breaks) chat to talk about any aspect of your classwork, college, life, etc. I have limited availability outside of these hours, but if these times don't work for your schedule, you can DM me **at least 1 week in advance** to arrange an alternate time. I'm unable to accommodate last-minute requests.

{: .important }
> I respond to async messages in Discord's text channels and DMs, and Pace emails &mdash; within 48 hrs during the week. Anything I get over the weekend, I'll respond to on Mon (I *might* reply sooner, but don't count on it). 
>
> For a quicker response to questions or project help, ask in #classroom or #team on Discord. Please note that I deprioritize questions about course material/logistics that are explained in the course syllabus and/or this website, or have already been asked and answered on Discord and added to the [FAQs](faqs){:target="_blank"} on this site.

{: .note }
> **All lecture notes will be linked in the calendar below after sync class sessions.**

{% for module in site.modules %}
{{ module }}
{% endfor %}
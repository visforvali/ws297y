---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 2
---

# Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`.

## Coffee Chats

I reserve 5 hours a week for by-appointment chats, but I'm often able to carve out time for DMs 

Drop-In Hour: Tue 2-5PM, Wed 12-2PM 🔉Café
Reserve 20min on Zcal: Mon 2-4PM, Thu 2-4PM
Or DM me for other times!

I respond to emails within 24 hrs during the week and to emails received over the weekend on Mon.

You can DM me on our class server or 


## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

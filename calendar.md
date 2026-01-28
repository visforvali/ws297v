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


<small>**Spring 2026**{: .label .label-blue-custom } **Wed 9:00AM - 12:00PM**{: .label .label-blue-custom } **Sync Text and Voice Chat**{: .label .label-blue-custom } **Discord**{: .label .label-blue-custom }</small>


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}


{: .warning }
> I reserve 5 hrs/wk for by-appointment coffee chats on Discord. You can book a 🕐10, 🕐15, or 🕧20 min chat with me over voice-and-video or voice-only (ideal for commutes and work breaks) to talk about any aspect of class, college, life, etc. Book early and often! And if these times don't work for your schedule, you can DM me to arrange an alternate time.
>
> You must contact me **at least 1 week in advance** to schedule a chat outside of my standard coffee chat times. I'm almost never able to accommodate last-minute requests.

{: .important }
> I respond to async messages &mdash; in #classroom, DMs, and email &mdash; within 48 hrs during the week. Anything I get over the weekend, I'll respond to on Mon (I *might* reply sooner, but don't count on it). 
>
> For a quicker response to questions or project help, ask in #classroom or #team on Discord. Please note that I deprioritize questions about course material/logistics that are explained in the course syllabus and/or this website, or have already been asked and answered on Discord and added to the [FAQs](faqs){:target="_blank"} on this site.

{: .note }
> **All slides are linked in the calendar next to their respective sync class sessions.**

{% for module in site.modules %}
{{ module }}
{% endfor %}
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

The schedule below approximates the "shape" of each week of this class (check the [Calendar](/calendar.md) for exceptions to this workflow and detailed descriptions of what we'll do). In addition to our regularly scheduled class time and my standard coffee chat availability, I've identified blocks of time when I *may* be available for quick (5-15 min) sync chats. These times vary from week to week, are only open to students who can't make my usual coffee chat hours, and aren't guaranteed, i.e. if my coffee chat times are fully booked, it doesn't mean I'll be able to find other times to meet.

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
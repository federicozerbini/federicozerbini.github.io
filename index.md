---
title: Home
show-avatar: false
layout: page
---

{% assign about= site.pages | where: 'name','aboutme.md' %}
{{about}}

# Upcoming talks

{% assign talks = site.pages | where: 'name','nexttalks.markdown' %}
{{talks}}
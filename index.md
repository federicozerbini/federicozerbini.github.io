---
title: Home
show-avatar: true
layout: page
---

{% assign about= site.pages | where: 'name','aboutme.md' %}
{{about}}

# Articles

{% assign talks = site.pages | where: 'name','publications.markdown' %}
{{talks}}

# Upcoming talks

{% assign talks = site.pages | where: 'name','nexttalks.markdown' %}
{{talks}}
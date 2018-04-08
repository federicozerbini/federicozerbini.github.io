---
title: Home
show-avatar: false
layout: page
---

{% assign about= site.pages | where: 'name','aboutme.md' %}
{{about}}

## Articles

{% assign Publications and preprints = site.pages | where: 'name','Publications and preprints.markdown' %}
{{Publications and preprints}}

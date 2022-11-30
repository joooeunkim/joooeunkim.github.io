---
title: "Projects2"
layout: archive
permalink: categories/project2
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.project2 %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}

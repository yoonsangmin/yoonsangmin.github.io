---
title: vocal
layout: archive_sort
permalink: categories/vocal
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.vocal %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
---
title: "JPA"
layout: archive
permalink: categories/jpa
author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories['jpa']%} {% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
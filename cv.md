---
layout: page
title:  CV
cover:  false
menu:   true
order:  5
---

{% include cv-list.html categories=site.data.cv.before-pubs %}
<h2>Publications</h2>
{% include paper-list.html venue='journal' heading='Journals' %}
{% include paper-list.html venue='conference' heading='Conferences' %}
{% include paper-list.html venue='workshop' heading='Workshops and Demonstrations' %}
{% include cv-list.html categories=site.data.cv.after-pubs %}



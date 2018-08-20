---
layout: page
title:  Papers
cover:  false
menu:   true
order:  1
---

> _I would have written a shorter letter, but I did not have the time._
>
> ---Blaise Pascal

<ul>
{% for paper in site.data.papers.papers %}
  <li>
  {% include paper.html paper=paper %}
  </li>
{% endfor %}
</ul>


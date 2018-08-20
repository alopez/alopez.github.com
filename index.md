---
layout: page
title: About me
cover: false
---

I develop computational models of natural language learning, 
understanding and generation in people and machines, and my research 
focuses on basic scientific problems related to these models. I am 
especially interested in modeling the rich diversity of linguistic
phenomena across the world’s languages. 

I am a [Reader](https://en.wikipedia.org/wiki/Reader_(academic_rank))
in the [Institute for Language, Cognition, and Computation](http://web.inf.ed.ac.uk/ilcc)
in the [School of Informatics](http://web.inf.ed.ac.uk/)
at the [University of Edinburgh](https://www.ed.ac.uk/). 
[My research group](collaborators.html) is part of the larger 
[Edinburgh natural language processing group](http://groups.inf.ed.ac.uk/edinburghnlp/)
and we collaborate with many people in Edinburgh and more widely. I am 
also the co-director of the 
[Centre for Doctoral Training in Data Science](http://datascience.inf.ed.ac.uk/), 
which offers a four-year MSc + PhD programme.

## News

* In June, my awesome PhD student [Sorcha Gilroy](http://homepages.inf.ed.ac.uk/s1459276/) 
received an [oustanding paper award](https://naacl2018.wordpress.com/2018/04/11/outstanding-papers/)
[NAACL 2018](http://naacl2018.org/) for a very cool
paper she coauthored on [RNNs as weighted language recognizers](http://aclweb.org/anthology/N18-1205). 
In the same month, she was a finalist in University of Edinburgh 
[3-minute thesis competition](https://www.ed.ac.uk/institute-academic-development/postgraduate/doctoral/3mt/3mt-final).

* Sorcha Gilroy and I taught a one-week course on 
[Graph formalisms for meaning representations](https://drive.google.com/drive/folders/1NtdhgieGKpnTvpYiBCUgkE-g0ygKDyE_) 
at [NASSLLI 2018](https://www.cmu.edu/nasslli2018/).
We will give a half-day tutorial on the same topic at 
[EMNLP 2018](http://emnlp2018.org/).

## Current Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>


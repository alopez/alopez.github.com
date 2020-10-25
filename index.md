---
layout: page
title: About me
cover: false
---
I am a research manager at [Rasa](https://rasa.com), where we are building
the standard infrastructure for conversational AI.
My [research](papers) interests are broad, and I have worked on many engineering, scientific,
and mathematical problems in natural language processing. 

I am also a [Reader](https://en.wikipedia.org/wiki/Reader_(academic_rank)) 
in the [Institute for Language, Cognition, and Computation](http://web.inf.ed.ac.uk/ilcc)
in the [School of Informatics](http://web.inf.ed.ac.uk/)
at the [University of Edinburgh](https://www.ed.ac.uk/), where I 
continue to advise [several PhD students](collaborators) in the
[Edinburgh natural language processing group](http://groups.inf.ed.ac.uk/edinburghnlp/).
I am no longer accepting new students.

## Recent News
* In July 2020, I joined the research team at [Rasa](https://rasa.com)! I'm [leading a new research and product hub in Edinburgh](https://www.prnewswire.com/news-releases/rasa-raises-26m-in-series-b-funding-led-by-andreessen-horowitz-301081571.html).
  
* In 2019, five of my PhD students successfully defended their theses:
  - [Sameer Bansal](https://0xsameer.github.io/), whose [thesis](https://era.ed.ac.uk/handle/1842/36781) was on 
    Low-Resource Speech Translation. He is now a researcher at Bloomberg.
  - [Arabella Jane Sinclair](https://staff.fnwi.uva.nl/a.j.sinclair/),
    whose [thesis](https://era.ed.ac.uk/handle/1842/37009) was on Modelling Speaker Adaptation in Second 
    Language Learner Dialogue. 
    She is now a postdoctoral researcher at the University of Amsterdam.
  - [Clara Vania](https://claravania.github.io/), whose [thesis](https://era.ed.ac.uk/handle/1842/36742) was 
    On Understanding Character-level Models for Representing Morphology.
    She is now a postdoctoral researcher at New York University.
  - [Nikolay Bogoychev](https://nbogoychev.com/),
    whose [thesis](https://www.era.lib.ed.ac.uk/handle/1842/35886) 
    was on Fast Machine Translation on Parallel and Massively Parallel 
    Hardware. 
    He is now a postdoctoral researcher at the University of Edinburgh.
  - [Sorcha Gilroy](https://uk.linkedin.com/in/sorcha-gilroy-a6105693), whose 
    [thesis](https://www.era.lib.ed.ac.uk/handle/1842/35606) was on 
    Probabilistic Graph Formalisms for Meaning Representations. 
    She is now a data scientist at Peak.ai.

## Recent Research Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>


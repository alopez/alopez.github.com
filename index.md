---
layout: page
title: About me
cover: false
---

I am a Reader (Associate Professor) 
in the [Institute for Language, Cognition, and Computation](http://web.inf.ed.ac.uk/ilcc)
in the [School of Informatics](http://web.inf.ed.ac.uk/)
at the [University of Edinburgh](https://www.ed.ac.uk/).
My [research](papers) interests are broad, spanning many engineering, scientific,
and mathematical problems in natural language processing.
I advise [several PhD students](collaborators) in the
[Edinburgh natural language processing group](http://groups.inf.ed.ac.uk/edinburghnlp/).
I am not accepting new students.

I have developed and taught [advanced courses in natural language processing](teaching)
at Edinburgh and at Johns Hopkins University. I also developed and taught
much of the training program for the 
[UKRI Centre for Doctoral Training in Natural Language Processing](https://nlp-cdt.ac.uk/).

## Recent News
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

* In September 2019, the 
[Centre for Doctoral Training in Natural Language Processing](https://edin.ac/cdt-in-nlp)
[welcomed its first students](https://twitter.com/EdinburghNLP/status/1173630819652579338)
The centre, directed by my colleague [Mirella Lapata](http://homepages.inf.ed.ac.uk/mlap/),
is a collaboration between informatics, linguistics, psychology, and design.
It offers an innovative new PhD programme that integrates research and 
teaching across these disciplines, and is supported in part by a 
multi-million pound [training grant from the UK government](https://www.ukri.org/research/themes-and-programmes/ukri-cdts-in-artificial-intelligence/). I am 
the co-director. 

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


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
[My research group](collaborators) is part of the larger 
[Edinburgh natural language processing group](http://groups.inf.ed.ac.uk/edinburghnlp/)
and we collaborate with many people in Edinburgh and more widely. 
I am also the co-director of the 
[Centre for Doctoral Training in Natural Language Processing](https://edinburghnlp.inf.ed.ac.uk/cdt/).


## Recent News
* In October 2019, [Sameer Bansal](https://0xsameer.github.io/)
successfully defended his PhD thesis on Low-Resource Speech Translation.
Sameer's thesis pushes the limits of what kind of system it is possible to 
build if you only  have a few hours of speech paired with translations, with
potential applications in language documentation and crisis response.

* In September 2019, [Arabella Jane Sinclair](https://staff.fnwi.uva.nl/a.j.sinclair/)
successfully defended her PhD thesis on Modelling Speaker Adaptation in Second 
Language Learner Dialogue. Arabella's thesis shows that students and tutors
adapt to each other in conversation across many different dimensions, and that
the nature of this adaptation depends on the student's ability. She is
now a postdoc at the University of Amsterdam.

* In September 2019, [Clara Vania](https://claravania.github.io/) successfully
defended her PhD theisis, On Understanding Character-level Models for Representing Morphology.
Clara's thesis carefully teases apart cases in which neural character-level
models successfully mimic the relationship between form and function in morphology,
and cases where they don't, across a variety of typologically different languages.
She is now a postdoc at New York University.

* In September 2019, the 
[Centre for Doctoral Training in Natural Language Processing](https://edin.ac/cdt-in-nlp)
[welcomed its first students](https://twitter.com/EdinburghNLP/status/1173630819652579338)
The centre, directed by my colleague [Mirella Lapata](http://homepages.inf.ed.ac.uk/mlap/),
is a collaboration between informatics, linguistics, psychology, and design.
It offers an innovative new PhD programme that integrates research and 
teaching across these disciplines, and is supported in part by a 
multi-million pound [training grant from the UK government](https://www.ukri.org/research/themes-and-programmes/ukri-cdts-in-artificial-intelligence/). I am 
the co-director. 

 * In April 2019, [Nikolay Bogoychev](https://nbogoychev.com/) successfully
defended his [PhD thesis](https://www.era.lib.ed.ac.uk/handle/1842/35886) on Fast Machine Translation on Parallel and 
Massively Parallel Hardware. Nick’s thesis shows how careful thinking about 
memory accesses yields simple and very effective algorithms for MT. He is 
now a postdoc at the University of Edinburgh.

* In January 2019, [Sorcha Gilroy](http://homepages.inf.ed.ac.uk/s1459276/) 
successfully defended her [PhD thesis](https://www.era.lib.ed.ac.uk/handle/1842/35606) on Probabilistic Graph Formalisms for
Meaning Representations. During her time as a student, she 
received an [oustanding paper award](https://naacl2018.wordpress.com/2018/04/11/outstanding-papers/)
at [NAACL 2018](http://naacl2018.org/) and was a finalist in University of Edinburgh 
[3-minute thesis competition](https://www.ed.ac.uk/institute-academic-development/postgraduate/doctoral/3mt/3mt-final),
along with many other accomplishments. She is now a data scientist at Peak.ai.

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


---
title: Bootstrapping Dependency Grammar Inducers from Incomplete Sentence Fragments
  via Austere Models
abstract: 'Modern grammar induction systems often employ curriculum learning strategies
  that begin by training on a subset of all available input that is considered simpler
  than the full data.  Traditionally, filtering has been at granularities of whole
  input units, e.g., discarding entire sentences with too many words or punctuation
  marks. We propose instead viewing inter-punctuation fragments as atoms, initially,
  thus making some simple phrases and clauses of complex sentences available to training
  sooner.  Splitting input text at punctuation in this way improved our state-of-the-art
  grammar induction pipeline.  We observe that resulting partial data, i.e., mostly
  incomplete sentence fragments, can be analyzed using reduced parsing models which,
  we show, can be easier to bootstrap than more nuanced grammars.  Starting with a
  new, bare dependency-and-boundary model (DBM-0), our grammar inducer attained 61.2%
  directed dependency accuracy on Section 23 (all sentences) of the Wall Street Journal
  corpus: more than 2% higher than previous published results for this task.'
pdf: http://proceedings.mlr.press/v21/spitkovsky12a/spitkovsky12a.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: spitkovsky12a
month: 0
tex_title: Bootstrapping Dependency Grammar Inducers from Incomplete Sentence Fragments
  via Austere Models
firstpage: 189
lastpage: 194
page: 189-194
order: 189
cycles: false
author:
- given: Valentin I.
  family: Spitkovsky
- given: Hiyan
  family: Alshawi
- given: Daniel
  family: Jurafsky
date: 2012-08-16
address: University of Maryland, College Park, MD, USA
publisher: PMLR
container-title: Proceedings of the Eleventh International Conference on Grammatical
  Inference
volume: '21'
genre: inproceedings
issued:
  date-parts:
  - 2012
  - 8
  - 16
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

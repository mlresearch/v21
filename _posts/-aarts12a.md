---
title: Learning and Testing the Bounded Retransmission Protocol
abstract: Using a well-known industrial case study from the verification literature,
  the bounded retransmission protocol, we show how active learning can be used to
  establish the correctness of protocol implementation $I$ relative to a given reference
  implementation $R$.  Using active learning, we learn a model $M_{R}$ of reference
  implementation $R$, which serves as input for a model based testing tool that checks
  conformance of implementation $I$ to $M_{R}$.  In addition, we also explore an alternative
  approach in which we learn a model $M_{I}$ of implementation $I$, which is compared
  to model $M_{R}$ using an equivalence checker.  Our work uses a unique combination
  of software tools for model construction (Uppaal), active learning (LearnLib, Tomte),
  model-based testing (JTorX, TorXakis) and verification (CADP, MRMC).  We show how
  these tools can be used for learning these models, analyzing the obtained results,
  and improving the learning performance.
pdf: "./aarts12a/aarts12a.pdf"
layout: inproceedings
key: aarts12a
month: 0
firstpage: 4
lastpage: 18
origpdf: http://jmlr.org/proceedings/papers/v21/aarts12a/aarts12a.pdf
sections: 
authors:
- given: Fides
  family: Aarts
- given: Harco
  family: Kuppens
- given: Jan
  family: Tretmans
- given: Frits
  family: Vaandrager
- given: Sicco
  family: Verwer
---

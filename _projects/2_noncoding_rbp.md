---
layout: page
title: Fitness impact of noncoding variants
description: Deep learning models of RNA-binding protein binding and post-transcriptional regulation (ongoing)
importance: 2
category: research
related_publications: false
---

**The idea.** Most variants in the genome are noncoding, and their functional impact is hard to measure directly. This project estimates the **fitness impact of noncoding variants from the human allele frequency spectrum**. It uses **RNA-binding protein (RBP) binding** and **cross-species conservation** as priors. A key component is a set of deep learning models that learn RBP binding across proteins and predict how variants alter post-transcriptional regulation.

**Current work**

- Training sequence models of RBP binding on ENCODE eCLIP data covering **168 RBPs**.
- Benchmarking the resulting variant effect scores against human allele frequency and existing predictors such as GPN-Star and AlphaGenome.
- Applying the model to _de novo_ UTR variants in autism and congenital heart disease cohorts. The goal is to test for case enrichment and to relate predicted binding-site disruption to selection coefficients outside conserved regions.

_This project is ongoing._

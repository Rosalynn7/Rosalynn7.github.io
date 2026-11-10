---
layout: page
title: Mutable & variant analysis pipelines
description: A public database of 79,000+ curated de novo variants, plus pipelines for early-onset disease analysis
importance: 5
category: research
related_publications: true
---

[**Mutable**](https://mutable.wiki) is a public, gene-centric database of **79,000+ curated _de novo_ variants** from published studies of neurodevelopmental disorders and congenital anomalies. I maintain and extend it. My work includes gene-based querying, variant-level annotation, and 3D visualization of spatial clustering among missense variants.

I also optimize variant analysis pipelines for database curation and clinical diagnostics:

- Support for multiple input formats (FASTQ, BAM/CRAM, VCF)
- Improved variant calling and quality control
- Functional annotation with gene- and variant-level constraint scores to help identify rare disease variants in early-onset cases

**Tools:** Nextflow, SAMtools, BCFtools, FreeBayes, DeepVariant, Docker, AWS

{% bibliography --cited_in_order --query @*[key=chen2026mutable]* %}

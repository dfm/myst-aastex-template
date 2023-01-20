---
title: An example AASTeX article
bibliography: example
authors:
  - name: Daniel Foreman-Mackey
    orcid: 0000-0002-9328-5652
    email: dforeman-mackey@flatironinstitute.org
    corresponding: true
    affiliations:
      - Center for Computational Astrophysics, Flatiron Institute, New York, NY, USA
  - name: Eric Agol
    orcid: 0000-0002-0802-9145
    email: agol@uw.edu
    affiliations:
      - Department of Astronomy, University of Washington, Seattle, WA, USA
      - Virtual Planetary Laboratory, University of Washington, Seattle, WA, USA
exports:
  - format: pdf
    template: ".."
    output: _exports/example.pdf
    style: modern
  - format: tex
    template: ".."
    output: _exports/example.tex
    style: modern
---

+++ { "part": "abstract" }

This is an example AASTeX article.

+++

# Introduction

{cite:t}`Luger:2019` is a great paper.

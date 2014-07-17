# Introduction

(other stuff first...)

Accurate visualization requires _multiple_ draws.
These can be superimposed on a single graph, but this creates tension between
visual clarity (fewer draws) and representative sampling (more draws).
The problem is especially severe for surfaces, where only a handful can be
shown before their mutual occlusion become hopelessly cluttered.

A helpful alternative is to show the draws in succession over time -- in other
words, to create an animation.

## Prior work

- Two approaches
  - Skilling (1991/2), Hennig (2013): great circles
  - ESG (1997): Statistically correct interpolation

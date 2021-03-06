# Abundance estimation using capture-recapture models

## What it does

This contains R code to estimate abundance using the Cormack-Jolly-Seber (CJS) model. 
I use [RMark](http://www.phidot.org/software/mark/docs/book/pdf/app_3.pdf) because everything can be done in R, 
and it's cool for reproducible research. 

I consider simple CJS models and models with transience. In passing, I also fit models with heterogeneity in the detection process 
using i) individual random effect and ii) with finite mixtures. The bootstrap is used to obtain confidence intervals. Multi-model inference is also illustrated using bootstrap to perform model selection.

## To do

* In the section with heterogeneity, check the calculations for `bigU` and `bigM` and make them generic.
* add Jolly-Seber as in [Karamanlidis et al. (2015)](https://oliviergimenez.github.io/pubs/Karamanlidisetal2015-Arcturos.pdf).
* add robust-design as in papers currently in reviews (including model selection with bootstrap).

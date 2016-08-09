# Abundance estimation using capture-recapture models

## What it does

This contains R code to estimate abundance using the Cormack-Jolly-Seber (CJS) model. 
I use [RMark](http://www.phidot.org/software/mark/docs/book/pdf/app_3.pdf) because everything can be done in R, 
and it's cool for reproducible research. 

I consider simple CJS models and models with transience. In passing, I also fit models with heterogeneity in the detection process 
with finite mixtures. The bootstrap is used to obtain confidence intervals. 

The data and codes are part of a manuscript that is currently in review:
> Chiara G. Bertulli, Loreleï Guéry, Niall McGinty, Ailie Suzuki, Naomi Brannan, Tania Marques, Marianne H. Rasmussen, Olivier Gimenez (in review). Abundance estimation of photographically identified common minke whales, white-beaked dolphins and humpback whales in Icelandic coastal waters using capture-recapture methods. 

## To do

* multi-model inference using bootstrap à la Buckland
* add complete reference for Chiara's paper once published
* models with individual random effects
* wolf example to illustrate abundance estimation with heterogeneity
* add Jolly-Seber as in [Karamanlidis et al. (2015)](https://dl.dropboxusercontent.com/u/23160641/my-pubs/Karamanlidisetal2015-Arcturos.pdf)
* add robust-design using data from papers currently in review


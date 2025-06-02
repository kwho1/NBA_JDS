# NBA_JDS
This repository contains the codes to reproduce the main results in the article "A Bayesian Negative Binomial-Bernoulli Model with Tensor Decomposition: Application for Jointly Analyzing Shot Attempts and Shot Successes in Basketball Games".  Below are the steps:

1.	To get the NBA shot chart data of a regular season, run the python code (modifying the year to download) on the top of the “Data Preparation.rmd” file, save as csv files.
2.	To obtain main results for a regular season: open “Data Preparation.rmd” and “Main3.rmd” in the same R session.  Input the year you want to investigate in the first block of “Data Preparation.rmd”, then run the remaining blocks.  Next run the block in “Main3.rmd”.  Result will be stored automatically.

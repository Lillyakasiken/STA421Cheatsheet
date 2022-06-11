# UZH Cheatsheet
Master Program in Biostatistics 


## STA421 Fundation of Bayesian Methodology FS22
There are 19 pages of cheat sheets that could print on **five double-sided A4 paper**.
 - Chapter 1: Classical vs Bayesian paradigms and conditional probability (2 pages)
 - Chapter 2: Conjugate Bayes, point estimates, and interval estimates (2 pages)
 - Chapter 3: Predictive distributions, asymptotics, and Monte Carlo simulations (4 pages)
 - Chapter 4: Markov chain and Monte Carlo methods (4 pages)
 - Chapter 5: JAGS and CODA (4 pages)
 - Chapter 6: Bayesian meta-analysis and empirical Bayes (3 pages)


To merge them in one PDF file:

```
gs -q -sPAPERSIZE=letter -dNOPAUSE -dBATCH -sDEVICE=pdfwrite -sOutputFile=BayesianCheatsheet.pdf Chapter1and2.pdf Chapter3.pdf Chapter4and5.pdf Chapter6.pdf
```

## STA408 Statistical Methods in Epidemiology FS22
**2 double-side A4 pages**

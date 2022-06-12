# UZH Cheatsheet (Master Program in Biostatistics)

Supposing you use the printer at University. It is recommended to select the `super-resolution` option in a printer.

Assuming you have git installed locally, you can check out the entire set of cheat sheets with the following command (from the command line):

```
git clone https://github.com/Lillyakasiken/UZH_Cheatsheet.git
```

and get updates by running `git pull` at any later time in the same directory.

Alternatively, for a ZIP file of the repository, you can click the `code` (green) button (top right of the main panel) and then click `Download ZIP`.

![Master Program in Biostatistics](uni_logo.png)



## [STA421 Fundation of Bayesian Methodology FS22](STA421_Foundations_of_Bayesian_Methodology/)
There are 19 pages of cheat sheets that could print on **five double-sided A4 paper**.
 - Chapter 1: Classical vs Bayesian paradigms and conditional probability (2 pages)
 - Chapter 2: Conjugate Bayes, point estimates, and interval estimates (2 pages)
 - Chapter 3: Predictive distributions, asymptotics, and Monte Carlo simulations (4 pages)
 - Chapter 4: Markov chain and Monte Carlo methods (4 pages)
 - Chapter 5: JAGS and CODA (4 pages)
 - Chapter 6: Bayesian meta-analysis and empirical Bayes (3 pages)


To merge them in one PDF file (from the command line):

```
gs -q -sPAPERSIZE=letter -dNOPAUSE -dBATCH -sDEVICE=pdfwrite -sOutputFile=BayesianCheatsheet.pdf Chapter1and2.pdf Chapter3.pdf Chapter4and5.pdf Chapter6.pdf
```

## STA408 Statistical Methods in Epidemiology FS22
**2 double-side A4 pages**

## Computational Statistics (ETHz) FS22
**1 double-side A4 page**

## STA110 Introduction to probability FS22
**1 double-side A4 page**

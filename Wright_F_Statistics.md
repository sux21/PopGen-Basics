# Some notes on Wright's F statistics

## Notations
### 3 variance components at 3 levels of a population
$\sigma^2_a$ = variance among subpopulations   
$\sigma^2_b$ = variance between individuals within a subpopulation  
$\sigma^2_w$ = variance within an individual  

### F~IT~, F~ST~, F~IS~
Variance components add up to total variance:
$\sigma^2_a$ + $\sigma^2_b$ + $\sigma^2_w$ = $\sigma^2$

Correlation of genes in an individual randomly picked from different subpopulations: 
$F_{IT}$ = $F$ = $\rho_{ab}$ = $\frac{\sigma^2_a + \sigma^2_b}{\sigma^2}$

Correlation of genes randomly picked in a subpopulation: 
$F_{ST}$ = $\theta$ = $\rho_a$ = $\frac{\sigma^2_a}{\sigma^2}$

Correlation of genes in an individual randomly picked in a certain subpopulation: 
$F_{IS}$ = $f$ = $\rho$~b~ = $\frac{F-\theta}{1-\theta}$ = $\frac{\sigma^2_b}{\sigma^2_b + \sigma^2_w}$

Note that variance among subpopulations ($\sigma^2_a$) is not relevant here because we are looking within subpopulations.

### Meanings of values of F~ST~
High $F$~ST~ means high variance of genes among subpopulations (high $\sigma^2_a$), meaning that subpopulations are have more different genes from each other.

### References
[Cockerham CC. Variance of gene frequencies. Evolution. 1969 Mar 1:72-84.](https://www.jstor.org/stable/2406485?seq=1)  
[Cockerham CC. Analyses of gene frequencies. Genetics. 1973 Aug;74(4):679.](https://pmc.ncbi.nlm.nih.gov/articles/PMC1212983/)  
[Weir BS, Cockerham CC. Estimating F-statistics for the analysis of population structure. evolution. 1984 Nov 1:1358-70.](https://www.jstor.org/stable/2408641?seq=1)  

# useR!2020
 
This reporsitory contains the materials for my poster presentation at useR!2020. 

I'm presenting the `implicitMeasures` R package, which is avalable on both [CRAN](https://cran.r-project.org/web/packages/implicitMeasures/index.html) and GitHub ([OttaviaE/implicitMeasures](https://github.com/OttaviaE/implicitMeasures)). 

## Scoring the implicit: The `implicitMeasures` package. 

During the past decades, social sciences have been showing a growing interest for the implicit investigation of attitudes. The Implicit Association Test (IAT; Greenwald et al., 1998) and the Single Category IAT (SC-IAT; Karpinski & Steinman, 2006) are the mostly used measures employed for this aim. Both measures result in a differential score (the *D-score*) expressing the respondents' bias in categorizing different stimuli under two contrasting conditions. Despite many R packages are available for computing IAT *D-score* algorithms, there are no packages for scoring the SC-IAT. Besides, the R packages for the computation of IAT *D-score* algorithms either do not provide all the available algorithms, or do not offer the chance to easily compare their results, or do not clearly disambiguate the specific algorithm they are computing, raising replicability issues. `implicitMeasures` is an R package that provides an easy way to score both the IAT and the SC-IAT, and to easily compare different IAT *D-score* algorithms. `implicitMeasures` supplies functions for plotting the results either at the individual or sample level, and for summarizing results statistics in convenient tables. 


# References

<div id="refs" class="references">

<div id="ref-Greenwald1998">

Greenwald, Anthony G, Debbie E McGhee, and Jordan L K Schwartz. 1998.
"Measuring Individual Differences in Implicit Cognition: The Implicit
Association Test." *Journal of Personality and Soclal Psychology* 74
(6): 1464-80. <https://doi.org/10.1037/0022-3514.74.6.1464>.

</div>

<div id="ref-karpinski2006">

Karpinski, Andrew, and Ross B. Steinman. 2006. "The Single Category
Implicit Association Test as a measure of implicit social cognition."
*Journal of Personality and Social Psychology* 91 (1): 16-32.
<https://doi.org/10.1037/0022-3514.91.1.16>.

</div>


</div>
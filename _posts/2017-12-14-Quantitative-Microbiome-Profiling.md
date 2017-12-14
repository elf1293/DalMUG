---
published: true
post_snippet: ...relative abundance data cannot be used to determine directional changes in taxa abundance or the biological relevance of these shifts. Vandeputte et al., attempt to solve this issue by measuring absolute bacterial loads of samples in combination with relative abundance information from 16S profiling to create quantitative microbiome profiles.
---

#### [Vandeputte et al., 2017, "Quantitative microbiome profiling links gut community variation to microbial load" Nature](https://www.nature.com/articles/nature24460)

_Summary of DalMUG group discussion written by:
**Jacob Nearing**_

### Summary
As many people in the field have already pointed out, there are glaring issues with using relative abundance data. One of the largest being that relative abundance data cannot be used to determine directional changes in taxa abundance or the biological relevance of these shifts. Vandeputte et al. attempt to solve this issue by measuring absolute bacterial loads of samples in combination with relative abundance information from 16S profiling to create quantitative microbiome profiles.

Two methods were tested to measure absolute bacterial loads: qPCR and fluorescence-activated cell sorting (FACS). The results from these two different methods were compared and were determined to be somewhat comparable (Ext Fig 1B). The authors decided to use FACS throughout the rest of the paper  “given its technical straightforwardness (limited number of technical manipulations; …), reproducibility, and throughput”.

Using this method to get total cell abundances enabled the authors to create quantitative microbiome profiles (QMP) by rarefying to a sample depth that was defined as the 16S rRNA gene copy-number-corrected sequencing depth divided by sample cell count. They went on to compare 40 healthy individuals using both QMP and relative microbiome profiles (RMP) and found significant differences. Furthermore, they found that Bacteroides is not significantly higher in Crohn's disease patients when looking at QMP data, but is when looking at RMP. This result is interesting as Bacteroides has been [linked to the disease](http://www.sciencedirect.com/science/article/pii/S1931312814000638) in the past through RMP analysis. 

Overall this paper presents a new and exciting method that can be used to get both quantitative and relative abundance values. Of course this method is not without its biases, so it may be hard to determine which data analysis pipeline can be trusted more. Further verification of this method with more mock communities may help answer this question as well as further comparisons of RMP vs QMP in different data sets. Given the opportunity there is no downside to using this method; however, you may get more bang for your buck by increasing your sample size rather than doing FACS for all your samples. 


### Points of interest
- It's good to know the bacterial load of a sample and that alone can be really useful for determining disease state (i.e Crohn’s disease patients have lower bacterial loads than normal)
- Enterotype Bacteroides 2 had significantly lower bacterial loads when compared to Bacteroides 1 and Ruminococcaceae enterotypes. 
- Ruminococcus was the only taxa significantly associated with increased cell counts
- QMP and RMP showed different co-occurrence patterns with only negative co-occurrences being seen in the RMP analysis. 
- QMP only agreed with three of the eight metadata correlations that RMP found



### Points of Confusion/Concern

- QMP analysis still does not answer a large question in the field about the practice of rarefying data
- Some bacterial cells could be smaller than the size capability of the FACS machine that was used. 
- The co-occurrence correlations were non-adjusted for confounding variables.
- Could have an issue with de novo otus in determine their 16S rRNA gene counts 
- Further validation between using FACS or qPCR to determine abundance and the effect of each method on creating QMPs would have been nice. 


---
published: true
post_snippet: ...different patterns of functional prevalence would be found if the RNA and DNA were analyzed separately.
title: Comparison of metatranscriptomes and metagenomes in adult men
---

#### [Abu-Ali et al. 2018. Metatranscriptome of human faecal microbial communities in a cohort of adult men. Nature Microbiology.](https://www.nature.com/articles/s41564-017-0084-4)

_Summary of DalMUG group discussion written by:
**Gavin Douglas**_

### Summary
Abu-Ali _et al._ present a comparison of a large dataset of metatranscriptomes (RNA) and metagenomes (DNA) from 
the stool of senior men as part of the “Health Professionals Follow-up Study”. As expected, stool RNA data is 
shown to be more variable than the DNA. In addition, the authors show that different patterns of functional 
prevalence would be found if the RNA and DNA were analyzed separately. This analysis is an important early step 
for comparing these data types and will be useful for researchers trying to make sense of their own multi-omics 
datasets. However, we had a number of issues with this paper. Our main problem was that there was not a clear 
discussion of the limitations and challenges of studying stool RNA. Although the authors discuss several interesting 
biological insights based on the ratio of RNA/DNA levels it is difficult to interpret the meaning of these differences
given the fast turnover in RNA expression levels that is likely occurring throughout the GI transit time.

### Points of Interest
* Only ~72 taxa were identified per sample with MetaPhlAn2 - this highlights a rarely discussed drawback of using shotgun metagenomics for taxonomic analysis (i.e. likely under-representation of the true number of species)

* Firmicutes were prevalent, in contrast to ELDERMET data: could this be related to the problem of comparing MGS and 16S data?

* Reassuring that the core and variable pathways are in biologically reasonable categories (e.g. metabolism is core, but specific AAs are variable).

* Use of Gini-Simpson index for summarizing alpha-diversity of taxa contributions to functions, which most of us had not seen before. Use of number of species instead may have been more interpretable and transparent.

* Surprising that more unclassified gene families were expressed than expected based on DNA. We would have expected higher expression of core, well-characterized gene families.

* The majority of both DNA and RNA reads could not be functionally classified - this makes it difficult to make strong claims about the functional “stability” of a community when so much is unknown.


### Points of Confusion
* Did not clearly describe sample collection that was discussed in the pilot study (this could have a big effect on RNA levels!)

* Median time for consecutive stool samples was 48 hours - is that normal for this age group (we would have expected ~24 hours)?

* Did not discuss why less RNA was classified at Uniref90 than DNA, could this be due to RNA viruses? More human contamination? Non-coding RNA?

* Most studies would aim for higher RNA sequencing depth in comparison to DNA, but was lower in this study.

* We were confused by the “weeks” labels in Fig. 5 - maybe this meant collection periods that were separated by the 6 months?

* Interesting to see same bacterial strains identified in different cohorts, but is this biased due to the use of the same reference databases? Does this tell us much about the % of bacterial strains that we can expect to be shared across cohorts?

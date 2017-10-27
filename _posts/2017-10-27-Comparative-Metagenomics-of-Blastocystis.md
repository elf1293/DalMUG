---
published: false
---
### Beghini F, Pasolli E, Truong TD, Putignani L, Cacciò SM, Segata N. 2017. Large-scale comparative metagenomics of Blastocystis, a common member of the human gut microbiome. ISME J 1–16. ([paper](https://www.nature.com/ismej/journal/vaop/ncurrent/full/ismej2017139a.html))

This paper is a great example of data-mining available shotgun metagenomics sequencing (MGS) datasets for novel inference. They focus on Blastocystis, a genus of unicellular eukaryotic microorganisms in the Stramenopile phylum. Morphologically strains are similar, but genetically can be extremely different. It tends to be more common in underdeveloped countries and has previously been associated with diseases like inflammatory bowel disease. The authors present guidelines for how Blastocystis (and other taxa) can be identified through MGS data. They convincingly argue that Blastocystis is part of the healthy gut microbiome. Overall this was an excellent paper and well worth reading. Below we highlight some points we found especially interesting or that we did not understand.

### Points of Interest
- As expected, Blastocystis prevalence differed geographically across datasets, e.g. low in China, but high in Africa

- At least 3 of the European datasets had overlapping samples (e.g. controls for IBD were obese samples in a different dataset). It looks like they acknowledge this in Figure 1 and de-replicated before statistical analyses, but this something to watch out for when analyzing these datasets.

- Blastocystis detection is related to the extraction protocols used  looks like it is one extraction protocol in particular which is poor for these species (phenol chloroform; Supp. Fig. 2)

- Given 50M reads they found a breadth of coverage of 10% to a genome corresponds to a limit of detection slightly below 0.03% abundance

- Interesting that Wilcoxon rank-sum tests were used to identify and exclude microbial associations

- The found 0 prevalence in Crohn’s disease patients.

- They identified core genes in 75% of analyzed genomes with identity > 65% over at least 600bp  9 genes, total of 21,984 bp used to build RAxML tree. The fact that these lenient cut-offs only identified 9 genes highlights what a strange genus this is… It could also be related to issues with the metagenomic sequencing missing genes as well when building de novo assemblies.

- Interesting application of RF to predict whether the rest of the microbiome can predict Blastocystis presence or not (it can!)

### Points of Confusion
- They first screened out non-Blastocystis DNA that in the reference genomes. We were surprised that there is so much contamination. Could this affect the past inferences of high levels of lateral gene transfer (LGT) in these species? Also we weren’t sure why 3% of the length of the contig was used as a cut-off to call as a contaminant.

- They mention that this detection threshold is better than PCR, which was surprising to us. We believe that qPCR can identify taxa at very low abundances (~1 in a million) so some additional clarification here would have been nice.

- Blastocystis is negatively associated with BMI, they say correlated, but we don’t think they actually ran correlations

- Blastocystis subtypes don’t seem to be replaced much. We understood their argument in the text, but found their comparison of abundances at 2 time-points to be difficult to interpret. They also included strains with < 10% coverage in this analysis, which seems to go against their pipeline.

- May have been some circularity in plotting tree based on how the subtypes are defined; wouldn’t it have been a red flag if the subtypes didn’t cluster together based on how they were identified?

- Also, they used different scales when plotting the subtrees, which is a little confusing

- Their assemblies are quite incomplete (they used a cut-off of at least 5Mb) the reference genome is 18.8 Mb, so they definitely have a restricted search space for finding core genes

- Problematic colouring in the heatmap dendrogram - branches and labels don’t match (the labels correctly match the sample IDs though so it doesn’t affect the interpretation)

_Summarized from DalMUG group discussion and written by:
**Gavin Douglas**_




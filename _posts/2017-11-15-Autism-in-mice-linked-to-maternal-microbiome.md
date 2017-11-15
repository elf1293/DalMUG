---
published: false
---
 
#### [Beghini et al., 2017, "Large-scale comparative metagenomics of Blastocystis, a common member of the human gut microbiome." ISME J](https://www.nature.com/ismej/journal/vaop/ncurrent/full/ismej2017139a.html)

### Summary
It has been shown in several animal models that activation of the maternal immune system (MIA), such as by viral infection, is associated with the development of neurological disorders in offspring. Epidemiological studies in humans have also suggested that maternal viral infection is associated with an increase in autism spectrum disorder (ASD). Earlier studies in mice have demonstrated a role for interleukin-17 (IL-17) in ASD-like phenotypes and abnormal cortical development. Here, Gloria Choi, Jun Huh and colleagues provide evidence that MIA-mediated abnormal behavioural phenotypes requires both the presence of segmented filamentous bacteria (SBF) and viral immune activation during pregnancy in mice. These two factors induce the differentiation of IL-17-producing T helper 17 (TH17) cells in pregnant mothers. Their offspring display behavioural abnormalities, which are associated with the presence of cortical patches in the somatosensory cortex of the brain. Overall, we thought this was a thorough analysis of a the interactions between gut microbiota and the host immune system in an interesting ASD mouse model.

### Points of Interest
- As expected, Blastocystis prevalence differed geographically across datasets, e.g. low in China, but high in Africa.

- At least 3 of the European datasets had overlapping samples (e.g. controls for IBD were obese samples in a different dataset). It looks like they acknowledge this in Figure 1 and de-replicated before statistical analyses, but this something to watch out for when analyzing these datasets.

- Blastocystis detection is related to the extraction protocols used looks like it is one extraction protocol in particular which is poor for these species (phenol chloroform; Supp. Fig. 2).

- Given 50M reads they found a breadth of coverage of 10% to a genome corresponds to a limit of detection slightly below 0.03% abundance.

- Interesting that Wilcoxon rank-sum tests were used to identify and exclude microbial associations.

- The found 0 prevalence in Crohn’s disease patients.

- They identified core genes in 75% of analyzed genomes with identity > 65% over at least 600bp 9 genes, total of 21,984 bp used to build RAxML tree. The fact that these lenient cut-offs only identified 9 genes highlights what a strange genus this is… It could also be related to issues with the metagenomic sequencing missing genes as well when building de novo assemblies.

- Interesting application of random forest to predict whether the rest of the microbiome can predict Blastocystis presence or not (it can!).

### Points of Confusion
- Maternal immune activation in mice as a model for ASD: No tests for learning which is an important part of the ASD phenotype

- Th-17 bacteria given to mice were isolated from UC patient (already primed for inflammation?)

- Did not profile whole microbiome using 16S or metagenomic sequencing – Jackson vs Taconic mice

- Researchers did not profile the immune markers or the microbiome in offspring


_Summarized from DalMUG group discussion and written by:
**Emily Lamoureux**_


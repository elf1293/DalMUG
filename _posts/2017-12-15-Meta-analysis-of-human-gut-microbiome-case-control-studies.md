---
published: true
title: Meta-analysis Of Human Gut Microbiome Case-control Studies
post_snippet: In this paper, Duvallet et al. present an effective way to conduct meta-analyses of 16S-based case-control studies of human-gut associated diseases. By reprocessing the datasets with a common bioinformatic pipeline and collapsing to the genus level, significant associations can be compared across studies for the same disease and across multiple studies of different diseases.
---

#### [Duvallet et al. 2017. Meta-analysis of gut microbiome studies identifies disease-specific and shared responses](https://www.nature.com/articles/s41467-017-01973-8?WT.mc_id=COM_NComms_1712_Alm)

_Summary of DalMUG group discussion written by:
**Karl Leuschen**_

### Summary

In this paper, Duvallet et al. present an effective way to conduct meta-analyses of 16S-based case-control studies of human-gut associated diseases. By reprocessing the datasets with a common bioinformatic pipeline and collapsing to the genus level, significant associations can be compared across studies for the same disease and across multiple studies of different diseases. This may yield additional insights compared to traditional data fusion techniques. Importantly, restricting the analysis to the genus level appears to smooth out technical artifacts and other confounders common to 16S-based microbiome studies of combined datasets (which may use different sequencing platforms, variable regions and bioinformatic pipelines).

Conducting a meta-analysis using the above method, the authors reproduced some of the findings of individual studies, showed interesting taxonomic associations in studies of the same disease, and found some taxa that appear to be generally associated with health and/or disease (i.e. found in more than one dataset and more than one disease).

As the authors are careful to point out, improving our understanding of the microbiome's role in health and disease will require larger samples sizes and more comprehensive patient-data in order to reduce the impact of confounding variables. This study is an important early indication that meta-analysis can be an effective way to address these issues.

### Points of Interest

- The authors are able to reproduce the findings of individual studies and increase confidence in some of the associations by studying the ones that hold across studies within the same disease.


- Stool transit time is shown to be a major potential confounder for biomarker discovery. The authors highlight the importance of good patient data in future studies of microbiome-associated diseases.


- Random forest classifiers were used as a rough marker for the amount of association the microbiome had with disease. More precise univariate analyses were conducted to find the taxa of significance within the datasets, but the machine learning approach helped to increase confidence that a true signal exists.


- The authors point to a group of taxa that share associations across datasets. These shared groups represent a large portion of the significant taxa across diseases, suggesting that they may be involved in a "healthy" or "dysbiotic" gut more generally.

### Points of Confusion

- "Healthy" and "pathogenic" microbes are discussed at several points in the paper, including suggestions about what types of therapy might work best for each microbe type. However, definitions of pathogenic and healthy microbes are lacking (especially at higher taxonomic levels, e.g. genus). These terms may best be left alone unless the benefit or harm is more directly quantifiable.


- Related to the last point, the authors suggest at least two general patterns for the differences between cases and controls: blooms of pathogenic microbes in some diseases and reduction in healthy microbes in others. These two types of shift only appear to have one representative disease each (among the diseases analyzed), and the number of significant taxa in most datasets are relatively low. It may have been worth it to feature these caveats more prominently.


- It was not completely clear why the chosen bioinformatic pipeline performed OTU clustering at 100% identity, particularly when genus level resolution was the goal. A few words about why this cutoff was chosen might have been helpful. The database used for taxonomic classification would also have been nice to know (the authors mention using the RDP classifier, but this can be used with other databases). Finally,  there is no mention of normalizing by sequencing depth across samples—either by rarefaction or using a statistical approach such as DeSeq2—which is normally a critical step in any 16S bioinformatic pipeline

---
published: true
post_snippet: [Parks et al.]look to fix problems with existing taxonomy... they propose a novel standardized bacterial taxonomy based on a concatenated protein phylogeny.
title: A novel standardized bacterial taxonomy based on genome phylogeny
---

#### [Parks et al., 2018. A proposal for a standardized bacterial taxonomy based on genome phylogeny. BioRxiv.](https://www.biorxiv.org/content/early/2018/01/31/256800)

_Summary of DalMUG group discussion written by:
**Casey Jones**_

### Summary
There are issues with the existing taxonomic frameworks used to assign taxa to sequenced samples during microbiome analyses. Historically, taxonomy was assigned to microbes based on their phenotypic and morphologic features. Even now that modern taxonomy is mostly guided by 16S rRNA gene trees, there are still many discrepancies yet to be addressed. 

Donovan Parks & colleagues from the University of Queensland look to fix these problems with a new taxonomy system. In their pre-print published on bioRxiv, they propose a novel standardized bacterial taxonomy based on a concatenated protein phylogeny. They name it the Genome Taxonomy Database (GTDB), which is publicly available online at http://gtdb.ecogenomic.org. The group plans to update the database bi-annually. 

To derive this taxonomy, they started with nearly 100,000 genomes from RefSeq/GenBank and metagenome assemblies. After dereplication, nearly 22K genomes remained, 40% of which (8,559) represented uncultured organisms. They then inferred a genome tree from this dereplicated dataset using an alignment of 120 ubiquitous single-copy proteins. 

Overall, they describe 99 phyla, including six major normalized monophyletic units from Proteobacteria. In all, 73% of taxa had one or more changes to their existing taxonomy. Our group was overall very satisfied with their work during our discussion, notwithstanding some issues about how it will be received by the scientific community. 


### Points of Interest
* 73% of the 84,634 genomes with NCBI taxonomy had 1 or more changes to their classification above species rank

* Success of this taxonomy will depend on uptake and acceptance by the research community which could be difficult. Incorporating GTDB in commonly used microbiome tools (e.g. QIIIME2 plugin) would facilitate usage and potentially gain traction of the database. 

* Could this new taxonomy be applied to older microbiome studies to see how results change, or are improved (case-control classification accuracies)? 


### Points of Confusion
* Relative evolutionary divergence (RED) metric was used to normalize assignment of higher taxonomy ranks. Is this metric robust enough to normalize ranks? 

* Will updating the tree bi-annually cause large shifts in taxonomy as more genomes are added to the tree? This could cause confusions about what version of the taxonomy is being used and what organism is actually being specified.

* The MGS-derived genomes are a high percent of their dereplicated set - how many changes to existing taxa would be made without them? This could be important if there are any fundamental problems with MGS-derived genomes. 

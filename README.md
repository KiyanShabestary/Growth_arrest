# Growth-arrest characterization

This folder contains all required files for the analysis of multi-omics data of growth-arrest Synechocystis lactate-producing strains . 


### Contents

**1. [Transcriptomics data work-up] (#transcriptomics) **

**2. [Proteomics data work-up] (#proteomics) **

<a name="transcriptomics"></a>
## Transcriptomics data work-up

Raw RNAseq data are processed as described below:

1. Data is trimmed, rRNA and tRNA reads are removed and filtered reads are assigned to the genome as described in [Ribopipe](https://github.com/Asplund-Samuelsson/ribopipe).

2. Reads are tabulated and DESeq2 is applied to calculate significance level and fold-change values.

#instructions and link to shell command


<a name="proteomics"></a>
## Proteomics data work-up

# Spatial biology tutorial

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Introduction

Spatially resolved genomics can be measured with various technologies that quantify the transcriptome, proteome or chromatin accessibility. However, these technologies vary in terms of scale, resolution, sensitivity, multiplexing and applicability. As the landscape of spatially resolved genomics is developing fast and is expected to change massively in the next few years, we are introducing only three overall groups of spatial omics technologies based on their capturing resolution. 

Broadly spoken, one can differentiate spatially resolved genomics into technologies that measure at multi-cell, single-cell and sub-cellular resolution. We will shortly motivate each of those scales and highlight their advantages and challenges and introduce the reader to a few technologies that fall into the respective category.


### Multi-cell resolution

Spatial omics data obtained at multi-cell resolution typically captures omics measurements among several cells. So, each datapoint contains information from a varying number of cells and also potentially different cell types. Multi-cell resolution data can be decomposed with deconvolution methods to obtain proportions of different cells or cell types per spot.
Multi-cell resolution data typically capture transcriptome-wide gene expression profiles at varying resolution. The obtained resolution for spot-based technologies varies between 55um (Visium) to 10 um (slide-seq). A widely known, commercially available and successful technology is Visium provided by 10x Genomics. We will showcase how to analyze and deconvolve Visium data in the tutorials.



## Analysis frameworks and tools
## Analysis pipline
### Preprocessing and visualization 
#### Normalization 
#### Dimensionality Reduction and clustering 

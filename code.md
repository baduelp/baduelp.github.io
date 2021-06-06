## SPLITREADER pipeline 
The scripts to detect non-reference transposable element insertions from short-read sequencing data, as described in Baduel et al. MMB 2021 [10.1007/978-1-0716-1134-0_15](https://doi.org/10.1007/978-1-0716-1134-0_15) are available on my public GitHub repository [here](https://github.com/baduelp/public/tree/master/SPLITREADER). <br/>
In addition, accessory files and wrapper scripts are available in [/thaliana](/SPLITREADER/thaliana) to run the SPLITREADER pipeline on the _A. thaliana_ genome. <br/> 

## MATLAB genomic toolbox
Custom MATLAB functions for genomics are available on my public GitHub repository [here](https://github.com/baduelp/public/tree/master/MATLAB). 

### Map of markers with color-coded values

<p align="center">
<img src="/images/Position of populations.png" >
</p>

<p align="justify">
<em>plot_POPmap_function.m</em>  
  
  This Matlab function displays markers on a world Mercator-projection map with color-coded values to display quantitative or categorical information. 
</p>  
  

### Principal Component Analysis (PCA) of Allele-Frequency population data

<p align="center">
<img src="/images/PC1 & 2 of fake PCA centered 23-Jun-2017.png" style="margin-right: 15px;" width="400">
</p>

<p align="justify">
<em>plot_AF_PCA.m</em>  
  
  This Matlab function performs a principal component analysis of allele-frequency population data from next-generation sequencing. It takes as input the N x M matrix containing for each of N sites the allele-frequency of derived alleles in each of the M individuals/populations.
</p>  
  


        

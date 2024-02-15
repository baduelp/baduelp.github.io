<br>

<p align="center"><img src="/images/seedling.png" width="120"></p>
<!-- <h1 align="center"> 🔬 <br><br>  </h1>--> 
  <h1 align="center"> Research </h1>

Our team studies the contribution of <b>transposable elements</b> (TEs) as a source of heritable allelic and epiallelic variation of functional importance and how it can be modulated by <b>genetic</b> as well as <b>environmental</b> determinants (axis 1)[#axis-1-genetic-and-environmental-determinants-of-transposition-in-nature],  <b>mating systems</b> (axis 2), or <b>ploidy</b> (axis 3). To tackle these questions, we use the  species of the  <em>Arabidopsis</em> genus, notably the model plant <em>A. thaliana</em> as a study system and combines multi-omic bioinformatic approaches with plant molecular genetics and field collections.

### Axis 1 - Genetic and environmental determinants of transposition in nature

Standing genetic variation is generally thought to be the main source of rapid adaptation to environmental changes. As a result, genomic studies aimed at estimating the evolutionary potential of native populations in future climates have mostly focused on SNPs. However, there is increasing evidence that the rare and typically large effect alleles created by TE insertions, even though mostly deleterious, can be sometimes beneficial and contribute significantly to local adaption. Leveraging the multi-omic and bio-climatic data for more than 1,000 wild <em>A. thaliana</em> accessions sequenced as part of the 1001 Genomes project, we set out to determine the rate of TE mobilization and its potential to create adaptive variation in natural settings. 

<img align="center" src="/images/GBIO_summary-fig.png" >

Using an updated pipeline to detect TE insertion polymorphisms (TIPs) from short-read sequencing data (see SPLITREADER package [here](code.md)), we identified >23,000 TIPs across >1000 accessions from across the globe. Based on this dataset, we determined the substitution rate of TIPs in nature to be almost a third of that of SNPs (between 0.06-0.08 TE insertion per genome per generation) and very close to the actual transposition rate we measured experimentally. However, unlike SNPs, TE insertions tend to have large deleterious effects when they insert within or near genes (which occurs at least 50% of the time for some TE families) and are therefore rapidly purged by purifying selection. Nonetheless, we found some gene loci to be recurrently targeted by TE insertions (most notably <em>FLC</em>’s 1st intron), and these tended to be found in disturbed environments where they showed signatures of positive selection.

Furthermore, we also found that a naturally truncated variant of <em>NRPE1</em> (a key component of the RdDM pathway which targets DNA methylation over TEs) causes lower CHH methylation and higher levels of transposition, largely by enhancing the environmental sensitivity (GxE) of TEs. Strikingly, this mutator <em>NRPE1</em> allele is enriched at the edge of the environmental niche of <em>A. thaliana</em> where it itself shows signature of positive selection, akin in a way to bacterial mutator alleles that can be temporarily beneficial in harsh environments. How such an allele has been retained over long term in <em>A. thaliana</em> opens exciting avenues of inquiry, especially in times of climate crisis where TEs may be essential genomic players in the demise or rescue of native populations.

#### Publications

**Baduel P**, Leduque B, Ignace A, Gy I, Gil J, Loudet O, Colot V, Quadrana L. _Genetic and environmental modulation of transposition shapes the evolutionary potential of Arabidopsis thaliana_. Genome Biology, [10.1186/s13059-021-02348-5](https://doi.org/10.1186/s13059-021-02348-5), 05/2021. 

**Baduel P**, Quadrana L. _Jumpstarting evolution: How transposition can facilitate adaptation to rapid environmental changes_. Current Opinion in Plant Biology, [10.1016/j.pbi.2021.102043](https://doi.org/10.1016/j.pbi.2021.102043), 04/2021.

**Baduel P** and Sasaki E. _The genetic basis of epigenetic variation and its consequences for adaptation_. Current Opinion in Plant Biology, [10.1016/j.pbi.2023.102409](https://doi.org/10.1016/j.pbi.2023.102409), 08/2023.

### Axis 2 - Impact of the mating type on TE mobilization dynamics

Theoretical considerations predict that TE dynamics are shaped in large part by the mating system (Wright and Schoen 1999), which in plants switches recurrently from outcrossing to selfing (Shimizu and Tsuchimatsu 2015). However, the direction of this effect remains unclear as changing mating system can have a number of consequences with potentially antagonizing influences on the dynamics of TEs (Boutin et al. 2012). On the one hand, selfing increases homozygosity compared to outcrossing, and thus exposes to purifying selection recessive deleterious alleles, such as those caused by most TE insertions (Arunkumar et al. 2015). On the other hand, the effective population size of selfers is expected to be drastically lower as compared to that of outcrossers, hence decreasing the efficacy of purifying selection against deleterious mutations (Pollack 1987). In addition, selfing is expected to limit the invasion of active TEs between genomes while outcrossing may favor instead an epidemic-like spread (Cavalier-Smith 1980). Finally, although the increased level of homozygosity in selfers results in lower effective homologous recombination rate, the actual frequency of crossovers is expected to be higher in selfers than in outcrossers (Roze and Lenormand 2005). How these different effects impact TE accumulation and ectopic recombination between dispersed TE copies is not known. Therefore, while theory predicts that mating systems play important roles in shaping TE dynamics (Wright et al. 2008), the net outcome of the balance between different forces, i.e. the nature of the deleterious effects of TEs (through recombination based processes or direct deleterious disruption of gene function) and their dominance/recessivity is generally unresolved.  

To study how mating systems impact the dynamics of TE accumulation, we used the outcrossing species _Arabidopsis lyrata_ which also has some North American populations that have recently experienced a shift to selfing. Specifically, we have sequenced from both selfing and outcrossing populations 20 genomes using long reads Oxford Nanopore Technology as well as 19 additional ones using short read Illumina sequencing. Using the short reads sequencing data, we have characterized the impact of selfing on genetic diversity as well as on the efficacy of purifying selection at the Single Nucleotide Polymorphism (SNP) level. After assembling the long-read sequenced genomes de novo, we have then detected transposable element insertion polymorphisms (TIPs) across these populations.

**Funding** This axis of research is part of the ANR PRC TE-MoMA (AAPG PRC 2018) led by Vincent Castric (Lille University) in collaboration with Vincent Colot (IBENS) and Jean-Marc Aury (Genoscope).

### Axis 3 - Impact of autopolyploidy on the epigenetic control of TEs 

Whole genome duplications (WGDs) are recurrent events throughout eukaryote evolution and the initial adaptive advantage they are associated with has been attributed in part to the increased genetic diversity of polyploid genomes (Baduel et al., _Front Ecol Evol_ 2018). Yet, the molecular mechanisms generating this diversity remain unclear. 

In this axis, we aim at investigating the role of transposable element (TE) mobilization in the rapid generation of genetic variation following WGD. Indeed, TEs are powerful generators of major-effect mutations with specific sensitivities to environmental stress, which confer them a unique potential to contribute to rapid local adaptations. Furthermore, the epigenetic mechanisms that control their mobilization, notably DNA methylation, is disrupted by WGD in several species. Thus, TEs could represent a major engine of phenotypic exploration for neo-polyploids, notably in the face of challenging environments.

<b>Funding:</b> This project is funded in part by the ANR JCJC POLYSTRESS grant (AAPG2023) as well as by a PhD fellowship from PSL University awarded to Mounia El Messaoudi. 




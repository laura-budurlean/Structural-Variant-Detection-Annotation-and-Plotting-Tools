# Structural-Variant-Detection-Annotation-and-Plotting-Tools

Useful tools for the analysis of structural variation (SV) in the genome. Includes tools used for SV detection, annotation, and plotting resources.

## Tools

### [ONCOFUSE](https://fusionhub.persistent.co.in/oncofuse.html)
Oncofuse can be used to annotate breakpoints of structural rearrangements and identify fusion genes. It is also designed to predict the oncogenic potential of fusion genes found by Next-Generation Sequencing in cancer cells. It is a post-processing step that tries to validate in-silico the predictions made by fusion detection software. Oncofuse is NOT a fusion detection software, its goal is NOT to identify fusion sequences, but to assign a functional prediction score (oncogenic potential, i.e. the probability of being 'driver' events) to fusion sequences identified by other software such as Tophat-fusion, fusioncatcher or STAR.

### [FusionHub](https://fusionhub.persistent.co.in/home.html)
Search for fusion gene pairs. "Owing to the availability of large number of public domain databases providing gene fusion information and lack of any search engine to collectively obtain information from these databases, we have developed FusionHub, a unified platform that simplifies large scale annotation of fusion genes. Additionally, to make FusionHub a centralized hub for all kind of gene fusion analysis, along with annotation module, two other features which are visualization and siRNA designing were also integrated."

### [AnnotSV](https://lbgi.fr/AnnotSV/runjob)
Annotation and ranking of SVs. Available as a web-based and command line tool. AnnotSV compiles functionally, regulatory and clinically relevant information and aims at providing annotations useful to i) interpret SV potential pathogenicity and ii) filter out SV potential false positives.

### [Circos](http://circos.ca/)
Circos can be used to plot and visualize translocation information and various other genomic annotations in a circular format. Circos is a software package for visualizing data and information. It visualizes data in a circular layout — this makes Circos ideal for exploring relationships between objects or positions. There are other reasons why a circular layout is advantageous, not the least being the fact that it is attractive.

### [FGviewer](https://ccsmweb.uth.edu/FGviewer/search)
"A tool for visualizing functional features of human fusion genes" Accepts a VCF file, gene names, or coordinate position information.

### [MapOptics](https://github.com/FadyMohareb/mapoptics)
"MapOptics is a lightweight cross-platform tool that enables the user to visualise and interact with the alignment of Bionano optical mapping data and can be used for in depth exploration of hybrid scaffolding alignments."

### [OMTools](https://github.com/TF-Chan-Lab/OMTools)
"A software package for optical mapping data processing, analysis and visualization"

### [ChimeRScope](https://pubmed.ncbi.nlm.nih.gov/28472320/)
"ChimeRScope: a novel alignment-free algorithm for fusion transcript prediction using paired-end RNA-Seq data"

### [FusionGDB 2.0](https://compbio.uth.edu/FusionGDB2/index.html)
FusionGDB is a database for searching and providing functional annotaion of fusion gene pairs occuring as a result of structural variation. 

### [LUMPY](https://github.com/arq5x/lumpy-sv)
LUMPY is a probabilistic framework for structural variant discovery. It integrates multiple signals to improve the sensitivity and specificity of SV detection.

### [Delly](https://github.com/dellytools/delly)
Delly is an integrated structural variant prediction method that can discover and genotype deletions, tandem duplications, inversions, and translocations at single-nucleotide resolution.
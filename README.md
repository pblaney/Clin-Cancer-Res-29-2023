# Clin-Cancer-Res-29-2023
Repository for analysis in "Multiomic Mapping of Acquired Chromosome 1 Copy-Number and Structural Variants to Identify Therapeutic Vulnerabilities in Multiple Myeloma" from  Boyle, E.M., Blaney, P., and Stoeckle, J. et al.

## Primary Analysis and Visualization

The crux of all data analysis and visualization were performed in `R` with the source code found in `quantitativeAnalysisOfEpigeneticLandscapeOnChromosome1.Rmd`. A knitted PDF version `quantitativeAnalysisOfEpigeneticLandscapeOnChromosome1.pdf` is also included to easily relate code blocks to figures included in the manuscript.

## Data Generation

### Copy-Number and Structural Variant Hotspots

The copy-number and structural variant hotspots were learned from WGS data of 752 MM patients enrolled in the [MMRF's CoMMpass trial](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000748.v7.p4) and originally described in [*Revealing the impact of structural variants in multiple myeloma* from Rustad et al.](doi.org/10.1158/2643-3230.BCD-20-0132).

### DNA Methylation

HumanMethylation27 array data was collected from peripheral blood derived B cells, plasma cells from non-malignant donors, patient samples of MGUS, NDMM, PCL, and 9 different myeloma cell lines originally described in [*Aberrant global methylation patterns affect the molecular pathogenesis and prognosis of multiple myeloma* from Walker et al.](doi.org/10.1182/blood-2010-04-279539).

### Hi-C

Hi-C data was obtained for normal B-cell states including peripheral blood derived naïve B-cells, memory B-cells, germinal-center B-cells, and tonsillar plasma cells from EGA dataset [EGAD00001006485](https://ega-archive.org/datasets/EGAD00001006485). Additional data was included for three myeloma cell lines from [GSE87585](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE87585) and [EGAD00001003597](https://ega-archive.org/datasets/EGAD00001003597).

### Super-Enhancers

Super-enhancer elements were characterized using H3K27ac signal peaks across 10 NDMM patients and U266, RPMI8226, and KMS11 cell lines as originally described in [*Myeloma-specific superenhancers affect genes of biological and clinical relevance in myeloma* from Jia et al](https://www.nature.com/articles/s41408-021-00421-7).

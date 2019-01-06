# MDS-16S rRNA

## Biological background
>Obesity, the accumulation of excess body fat has a negative impact on morbidity, mortality, and quality of life through its complications, which include cardiovascular disease, type 2 diabetes, osteoarthritis, and certain cancers.The etiology of obesity and its metabolic complications, including hyperlipidemia, hypertension, glucose intolerance and diabetes reflect the complex interactions of multiple genetic, behavioral, and environmental factors. Great inter-individual variation is apparent in the propensity toward obesity, the location where excess fat is deposited, and the extent to which this results in metabolic derangements and adverse health outcomes.

>To explore the possible dysbiosis of gut microbiota in obesity and its metabolic complications in humans, we studied Old Order Amish subjects from Lancaster County, Pennsylvania.

>There is great uniformity of socioeconomic status and lifestyle among the Amish, and prescription medication usage is minimal, reducing the potentially confounding influences of variation in environmental exposures on complex traits. Extensive genealogies document a small number of founders and genetic analyses confirm less genetic heterogeneity relative to the general population. These attributes make the Amish a highly desirable population in which to study the composition of the gut microbiota, its heritability, and its relationship to obesity and metabolic complications.
*************************************

## Data description
[paper related](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3419686/#)

[reads download website](https://www.ncbi.nlm.nih.gov/Traces/study/?acc=phs000258)

<table><tr><td bgcolor=#D1EEEE>human feces</td></tr></table>

<table><tr><td bgcolor=#D1EEEE>16s rRNA V2 region sequencing (454 pyrosequencing)</td></tr></table>

**three age- and sex-matched groups from the Old Order Amish.**  (problematic)

(1)	50 obese subjects (BMI >30 kg/m2) with one or more dysmetabolic manifestations

(2)	50 obese subjects (BMI > 30kg/m2) without any dysmetabolism manifestation

(3)	50 nonobese subjects (BMI < 25kg/m2) without any features of metabolic syndrome
*****************************

## Sample processing
Sample reads are processed using **mothur v.1.27.0** and **scripts** are showed
******************************

## Files for statistical analysis
**files information**

./data_for_analysis/

(1) 944 out of all 1082 samples tree files : 1tree.zip & 2tree.zip & 3tree.zip (>25M,thus splitted)

(2) 944 out of all 1082 samples otu profiles

**covariates information**

(1) file 16Smetadata

(2) metadata linkage
ftp://ftp.ncbi.nlm.nih.gov/dbgap/studies/phs000258/phs000258.v1.p1/pheno_variable_summaries/phs000258.v1.pht001242.v1.HMP_Gut_Obesity_Sample_Attributes.data_dict_2010_06_09.xml
***********************************

### References:
1. *Fraser-Liggett C M, Shuldiner A R. The Thrifty Microbiome: The Role of the Gut Microbiota in Obesity in the Amish[J]. 2010.*

2. *Schloss, P.D., et al., Introducing mothur: Open-source, platform-independent, community-supported software for describing
and comparing microbial communities. Appl Environ Microbiol, 2009. 75(23):7537-41.*




# Iron-circadian crosstalk in the murine gut microbiome

Completed as part of Specialist Research Project in Multi-Omics and Data Science (BIOC0023) for BSc Biochemistry at UCL, 2024-25.  
This repository hosts a reproducible Snakemake workflow for processing and analysing 16S rRNA amplicon sequencing data (V3-V4) generated for a pilot survey of the theme.

## Rationale
- Luminal iron availability rapidly remodels microbial communities.
- Hepcidin (*Hamp*) governs systemic iron and exhibits circadian expression in liver.
- Previous iron-microbiome studies reported compositional shifts, but the temporal impact of chronic iron overload remains unexplored.

## Scientific question
  Does chronic systemic iron overload (liver‑specific *Hamp* knockout) reshape the daily oscillations of the murine gut microbiome in a location‑dependent manner?

## Experimental design
- **Mouse model**: Male *Hamp*<sup>fl/fl</sup>; Alb-Cre<sup>ERT2+/–</sup> (tamoxifen‑induced KO, “HET”) vs *Hamp*<sup>fl/fl</sup>; Alb-Cre<sup>ERT2–/–</sup> (wild-type, “WT”)
- **Sampling**: 12h : 12h light/dark housing - samples taken at ZT10 (17:00) and ZT22 (05:00)
- **Gut regions**: faeces, ileum, duodenum

## Main findings
- Small sample size limited statistical power
- Day‑night oscillation in WT is dampened or reversed in HET.
- Largest shifts were observed in duodenum.
- Firmicutes/Bacteroidetes (F/B) ratio change is reversed in HET mice. 

## Acknowledgments
I would like to extend my gratitude to Dr Toryn Poolman, UCL for his advice and support throughout the project.  
The knockout mice were a kind gift from Prof David Ray, University of Oxford.

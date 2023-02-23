# Prenatal vitamin intake in first month of pregnancy and DNA methylation in cord blood and placenta in two prospective cohorts 

John F. Dou, Lauren Y.M. Middleton, Yihui Zhu, Kelly S. Benke, Jason I. Feinberg, Lisa A. Croen, Irva Hertz-Picciotto, Craig J. Newschaffer, Janine M. LaSalle, Daniele Fallin, Rebecca J. Schmidt, Kelly M. Bakulski

## Citation Information
Dou JF, Middleton LYM, Zhu Y, Benke KS, Feinberg JI, Croen LA, Hertz-Picciotto I, Newschaffer CJ, LaSalle JM, Fallin MD*, Schmidt RJ*, Bakulski KM*. 2022. Prenatal vitamin intake in first month of pregnancy and DNA methylation in cord blood and placenta in two prospective cohorts. Epigenetics & Chromatin. PMID: 35918756, PMCID: PMC9344645

This Github repository contains the data management and analytic scripts to produce the following manuscript: [Prenatal vitamin intake in first month of pregnancy and DNA methylation in cord blood and placenta in two prospective cohorts](https://epigeneticsandchromatin.biomedcentral.com/articles/10.1186/s13072-022-00460-9)

**Background**: Prenatal vitamin use is recommended before and during pregnancies for normal fetal development. Prenatal vitamins do not have a standard formulation, but many contain calcium, folic acid, iodine, iron, omega-3 fatty acids, zinc, and vitamins A, B6, B12, and D, and usually they contain higher concentrations of folic acid and iron than regular multivitamins in the U.S. Nutrient levels can impact epigenetic factors such as DNA methylation, but relationships between maternal prenatal vitamin use and DNA methylation have been relatively understudied. We examined use of prenatal vitamins in the first month of pregnancy in relation to cord blood and placenta DNA methylation in two prospective pregnancy cohorts: the Early Autism Risk Longitudinal Investigation (EARLI) and Markers of Autism Risk Learning Early Signs (MARBLES) studies.

**Results**: In placenta, prenatal vitamin intake was marginally associated with -0.52% (95% CI: -1.04, 0.01) lower mean array-wide DNA methylation in EARLI, and associated with -0.60% (-1.08, -0.13) lower mean array-wide DNA methylation in MARBLES. There was little consistency in the associations between prenatal vitamin intake and single DNA methylation site effect estimates across cohorts and tissues, with only a few overlapping sites with correlated effect estimates. However, the single DNA methylation sites with p-value<0.01 (EARLI cord nCpGs =4,068, EARLI placenta nCpGs =3,647, MARBLES cord nCpGs =4,068, MARBLES placenta nCpGs =9,563) were consistently enriched in neuronal developmental pathways.

**Conclusions**: Together, our findings suggest that prenatal vitamin intake in the first month of pregnancy may be related to lower placental global DNA methylation and related to DNA methylation in brain-related pathways in both placenta and cord blood.

## Funding
Nutrient and DNA methylation measures and analyses were supported by the National Institutes of Health (R01 ES025574, PI: Schmidt). Cord blood DNA methylation was also funded by R01 ES025531, PI: Fallin. Funding for the EARLI study was provided by the National Institutes of Health (R01ES016443, PI: Newschaffer) and Autism Speaks (003953 PI: Newschaffer). The MARBLES study was funded by National Institutes of Health grants (R24ES028533, R01ES020392, R01ES028089, R01ES020392, P01ES011269) and an EPA STAR grant (#RD-83329201). Support for this research was also provided by the National Institutes of Health grants (P30 ES017885 and R24 ES030893, PI: Fallin). Mr. Dou and Dr. Bakulski were also supported by grants (R01 ES025531, PI: Fallin; R01 AG067592, MPI: Bakulski; R01 MD013299). Dr. Zhu and Dr. LaSalle were supported by R01 ES029213. The content is solely the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health.

## Script files:

Processing.Rmd - Sample and probe filtering

EARLI_CORD_PV.Rmd - Model fitting for EARLI Cord Blood

EARLI_PLACENTA_PV.Rmd - Model fitting for EARLI Placenta

MARBLES_CORD_PV.Rmd - Model fitting for MARBLES Cord Blood

MARBLES_PLACENTA_PV.Rmd - Model fitting for MARBLES Placenta

EARLI_MARBLES_compare.Rmd - Comparing results and creation of main figures

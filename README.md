# PhD-tasks

Description main files:

**1. Poster_workshop_PG_normal.PDF:** PDF file for the poster presentation in the workshop the 3th of February, 2023.

**2. Poster_workshop_PG_audio.ppt:** .ppt file containg the poster information and an additional explanation of specific aspects that are not described in the poster

**Additional information to read the poster:**

**Sample of the study:** in the sample of the study, we classified cognitively unimpaired individuals as Aβ- and Aβ+. Amyloid-beta plaques acumulation is a well known hallmark of Alzheimer's disease and the quantification of CSF Aβ42 levels allow us to establish a specific threshold (CSF Aβ42/40<0.0071) to distinguish between individuals presenting (Aβ+) or not (Aβ-) AD-related pathology. For more information related to AD core biomarkers see [Milà-Alomà et al., 2020] [https://pubmed.ncbi.nlm.nih.gov/32573951/]

**Compositional data analysis methods:** brain subregions volumes were defined as components of a composition.  Through a cross-validation procedure, the algorithm selected the lambda value to perform the elastic net penalized regression procedure. The association between pairwise log-ratios and higher risk of AD was assessed and an optimal multiavariate brain structural variation signature was defined as a log-contrast function (Mi). This  signature was defined as a predictor variable in a logistic model where the outcome was the binary PRS-AD (High vs Low risk of AD). The contribution of each one of the brain subregions volumes to the brain signature was defined by summing the beta coefficients for each one of the selected components in the elastic net regression and standardizing them. 

**Figure 4.** Regarding the definition of the brain signature as a multivariate measure, we need to understand the joint volumetric modulation of the coloured brain regions in a multivariate way. The coefficient shown in the legend refers to the contribution of the region to the brain signature (standardized sum of betta coefficients that we have described above). This plot is helpful for researchers in the neuroscience field to visually inspect whether the algorithm has been able to detect joint modulations  of subregions involved in specific memory networks. 

**Figure 5.** In figure 5 we plot exactly the same information than in Figure 4, showing the weight of each brain region involved in the optimal brain signature. 


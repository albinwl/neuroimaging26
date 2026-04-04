# neuroimaging26

### Group information
Group 10 \
Albin Fredrik Wickman Lundberg (ist1119353) \
Ana Beatriz Machado (ist1119776)\
Bianca Cornaggia (ist1119620)\
Don Enrico Buebos Esteve (ist1118650)\
Jose Enrique Lopez (ist1118909)

### Abstract

Parkinson's disease (PD) is a progressive neurodegenerative disorder caused by the loss of dopaminergic neurons in the substantia nigra, resulting in motor symptoms such as tremors, stiffness, and bradykinesia. In this project, we investigated how PD affects brain morphometry in the putamen, amygdala, and hippocampus using structural MRI, and Default Mode Network (DMN) connectivity using resting-state fMRI. Two subjects—one PD patient with normal cognition (PD-NC) and one healthy control (HC)—from the public OpenNeuro ds005892 dataset were analysed using a Neurodesk pipeline.

For the structural analysis, the pipeline included skull stripping, tissue segmentation into white matter (WM), grey matter (GM), and cerebrospinal fluid (CSF), volume extraction of the three regions of interest, and registration to the Montreal Neurological Institute (MNI152) standard space.

For the functional analysis, key preprocessing steps included B0 unwarping, motion correction, and nuisance regression of motion parameters, motion outliers, and WM/CSF signals. The independent component (IC) best matching the DMN was identified based on the maximum Dice coefficient overlap with Yeo's 7-network DMN template.

We found volume loss in the three studied regions and reduced connectivity in the DMN in the PD-NC subject compared to the HC. However, owing to the minimal sample size, no conclusions can be drawn, and all analyses remain speculative.

### Bibliography 
[1] National Health Service. “Symptoms - Parkinson’s Disease.” NHS, NHS, 3 Nov. 2022, www.nhs.uk/conditions/parkinsons-disease/symptoms/

[2] Ghandili, Mehrnoosh, and Sunil Munakomi. “Neuroanatomy, Putamen.” PubMed, StatPearls Publishing, 2020, www.ncbi.nlm.nih.gov/books/NBK542170/

[3] Laansma, Max A., et al. “A Worldwide Study of Subcortical Shape as a Marker for Clinical Staging in Parkinson’s Disease.” Npj Parkinson’s Disease, vol. 10, no. 1, 19 Nov. 2024, www.nature.com/articles/s41531-024-00825-9, https://doi.org/10.1038/s41531-024-00825-9

[4] Halliday, Glenda, and Karen Murphy. “Pathology of Parkinson’s Disease.” MOVEMENT DISORDERS 4, 2010, pp. 132–154, https://doi.org/10.1016/b978-1-4160-6641-5.00009-x

[5] Cleveland Clinic. “Hippocampus.” Cleveland Clinic, 14 May 2024, my.clevelandclinic.org/health/body/hippocampus.

[6] Rosenberg-Katz, Keren, et al. “Subcortical Volumes Differ in Parkinson’s Disease Motor Subtypes: New Insights into the Pathophysiology of Disparate Symptoms.” Frontiers in Human Neuroscience, vol. 10, 10 July 2016, https://doi.org/10.3389/fnhum.2016.00356. Accessed 2 May 2025.

[7] Lucas-Jiménez, Olaia, et al. “Altered Functional Connectivity in the Default Mode Network Is Associated with Cognitive Impairment and Brain Anatomical Changes in Parkinson’s Disease.” Parkinsonism & Related Disorders, vol. 33, Dec. 2016, pp. 58–64, https://doi.org/10.1016/j.parkreldis.2016.09.012

[8] Tripathi, Vaibhav, et al. “Default Mode Network Functional Connectivity as a Transdiagnostic Biomarker of Cognitive Function.” Biological Psychiatry: Cognitive Neuroscience and Neuroimaging, vol. 10, no. 4, 9 Jan. 2025, pp. 359–368, www.sciencedirect.com/science/article/abs/pii/S2451902225000151, https://doi.org/10.1016/j.bpsc.2024.12.016

[9] Pai, M., Lu, W., Chen, M., & Xue, B. (2023). “The association between subjective cognitive decline and trajectories of objective cognitive decline: Do social relationships matter?” Archives of Gerontology and Geriatrics, 111, 1–14.

[10] Aaron S. Kemp, A. Journey Eubank, Yahya Younus, James E. Galvin, Fred W. Prior, Linda J. Larson-Prior, “Sequential patterning of dynamic brain states distinguish Parkinson’s disease patients with mild cognitive impairments”, NeuroImage: Clinical, Volume 46, 2025.

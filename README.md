#  Brain Morphometry and Network Function: Structural MRI and Resting-State fMRI

### Group information
Group 10 \
Albin Fredrik Wickman Lundberg (ist1119353) \
Ana Beatriz Machado (ist1119776)\
Bianca Cornaggia (ist1119620)\
Don Enrico Buebos Esteve (ist1118650)\
Jose Enrique Lopez (ist1118909)

### Abstract
Parkinson's disease (PD) is a progressive neurodegenerative disorder[1,3]. In this project, we investigated how PD affects brain morphometry in the putamen [2], amygdala, and hippocampus using structural MRI, and Default Mode Network (DMN) connectivity using resting-state fMRI [4,5]. Two subjects — one PD patient with normal cognition (PD-NC) and one healthy control (HC) — from the public OpenNeuro ds005892 dataset [6] were analysed in a Neurodesk environment [9–12].

For the structural analysis, the pipeline included skull stripping, tissue segmentation into white matter, grey matter, and cerebrospinal fluid, volume extraction of the three regions of interest, and registration to the Montreal Neurological Institute (MNI152) standard space [7].

For the functional analysis, key preprocessing steps included B0 unwarping, motion correction, and nuisance regression. The independent component best matching the DMN was identified based on the maximum Dice coefficient overlap with Yeo's 7-network DMN template [8].

We found volume loss in all three regions and reduced connectivity in the DMN in PD-NC compared to HC. However, owing to the minimal sample size, no generalised conclusions can be drawn.

### Bibliography 

[1] National Health Service. “Symptoms - Parkinson’s Disease.” NHS, NHS, 3 Nov. 2022, www.nhs.uk/conditions/parkinsons-disease/symptoms/.

[2] Ghandili, Mehrnoosh, and Sunil Munakomi. “Neuroanatomy, Putamen.” PubMed, StatPearls Publishing, 2020, www.ncbi.nlm.nih.gov/books/NBK542170/.

[3] Halliday, Glenda, and Karen Murphy. “Pathology of Parkinson’s Disease.” MOVEMENT DISORDERS 4, 2010, pp. 132–154, https://doi.org/10.1016/b978-1-4160-6641-5.00009-x.

[4] Lucas-Jiménez, Olaia, et al. “Altered Functional Connectivity in the Default Mode Network Is Associated with Cognitive Impairment and Brain Anatomical Changes in Parkinson’s Disease.” Parkinsonism & Related Disorders, vol. 33, Dec. 2016, pp. 58–64, https://doi.org/10.1016/j.parkreldis.2016.09.012.

[5] Tripathi, Vaibhav, et al. “Default Mode Network Functional Connectivity as a Transdiagnostic Biomarker of Cognitive Function.” Biological Psychiatry: Cognitive Neuroscience and Neuroimaging, vol. 10, no. 4, 9 Jan. 2025, pp. 359–368, www.sciencedirect.com/science/article/abs/pii/S2451902225000151, https://doi.org/10.1016/j.bpsc.2024.12.016.

[6] OpenNeuroDatasets. “GitHub - OpenNeuroDatasets/Ds005892: OpenNeuro Dataset - Resting State MRI Data from Healthy Control (HC), Parkinson’s Disease with Normal Cognition (PD-NC), and Parkinson’s Disease with Mild Cognitive Impairment (PD-MCI) Cohorts.” GitHub, 2025, github.com/OpenNeuroDatasets/ds005892/tree/main.

[7] Centre, McConnell Brain Imaging. “BIC - the McConnell Brain Imaging Centre: ICBM 152 N Lin 2009.” Www.bic.mni.mcgill.ca, www.bic.mni.mcgill.ca/ServicesAtlases/ICBM152NLin2009.

[8] “CorticalParcellation_Yeo2011 - Free Surfer Wiki.” Surfer.nmr.mgh.harvard.edu, surfer.nmr.mgh.harvard.edu/fswiki/CorticalParcellation_Yeo2011.

[9] van Rossum, Guido, and Fred L Drake. Python 3 : Reference Manual. United States, Sohobooks, 2009.

[10] Abraham, Alexandre, et al. “Machine Learning for Neuroimaging with Scikit-Learn.” Frontiers in Neuroinformatics, vol. 8, 2014, https://doi.org/10.3389/fninf.2014.00014.

[11] Brett, Matthew, et al., “Neuroimaging in Python — NiBabel 2.4.0 Documentation.” Nipy.org, 2019, nipy.org/nibabel/.

[12] Hunter, John D. “Matplotlib: A 2D Graphics Environment.” Computing in Science & Engineering, vol. 9, no. 3, 2007, pp. 90–95, ieeexplore.ieee.org/document/4160265.

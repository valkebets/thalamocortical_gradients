# Thalamocortical gradients


### Motivation

Autism spectrum disorder (ASD) is a neurodevelopmental diagnosis characterized by social and communication impairment, as well as restrictive and repetitive interests (Hodges et al., 2020). Previous neuroimaging studies have reported both atypical structural and functional brain organization in this condition, but it remains challenging to characterize the substrate of autism. In an effort to characterize cortical function, a recent resting-state functional magnetic resonance imaging study revealed atypical functional connectome hierarchy in ASD, reflecting atypical transitions between sensory and higher cognitive networks (Hong et al., 2019). The thalamus is a central subcortical structure, and has been suggested as a hub mediating cortico-cortical integration and sustaining cortical hierarchy (Jones 2001, Shine 2021). How this structure contributes to atypical cortical function in ASD, on the other hand, remains incompletely understood. Here, we profiled thalamo-cortical connectivity in individuals with ASD, capitalizing on novel approaches that simultaneously capture thalamo-cortical connectivity in a compact lower dimensional space.


### Use

The `code` folder contains notebooks for :
* creating a symmetric mask of the thalamus
* extracting timeseries from the thalamus (within the previously created mask) and cortex (Schaefer 400 parcellation; Schaefer et al. ,2018)
* computing functional connectivity (FC) between the thalamus and cortex
* computing gradients derived from thalamo-cortical FC
* assessing group differences in gradients between individuals with ASD and typically developing individuals using linear models
* visualizing gradients & group differences

The `data` folder contains the surface map in Conte69 (20'484 vertices total) and a `csv` file with the sample demographics


### References

* Hodges H, Fealko C, Soares N (2020) [Autism spectrum disorder: definition, epidemiology, causes, and clinical evaluation](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7082249/). Translational Pediatrics, 9(Suppl 1), S55–S65.

* Hong SJ, Vos de Wael R, Bethlehem RAI, Larivière S, Paquola C, Valk SL, Milham MP, Di Martino A, Margulies DS, Smallwood J, Bernhardt BC (2019) [Atypical functional connectome hierarchy in autism](https://doi.org/10.1038/s41467-019-08944-1). Nature Communications, 10, 1022. 

* Jones EG (2001) [The thalamic matrix and thalamocortical synchrony](https://doi.org/10.1016/S0166-2236(00)01922-6). Trends in Neurosciences, 24(10), 595-601. 

* Schaefer A, Kong R, Gordon EM, Laumann TO, Zuo XN, Holmes AJ, Eickhoff SB, Yeo BTT (2018) [Local-global parcellation of the human cerebral cortex from intrinsic functional connectivity MRI](https://doi.org/10.1093/cercor/bhx179). Cerebral Cortex, 28(9), 3095–3114.

* Shine JM (2021) [The thalamus integrates the macrosystems of the brain to facilitate complex, adaptive brain network dynamics](https://doi.org/10.1016/j.pneurobio.2020.101951). Progress in Neurobiology, 199, 101951. 

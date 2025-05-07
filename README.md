# neurotype
Interactive generative AI webapp that creates animated rs-fMRI brain visuals based on user traits (age, sex, personality). Pretrained a CLIP-style multimodal transformer to align neuroimaging and psychometric profiles into a shared latent space. Used DiT-based diffusion models to synthesize and animate neuroimaging data from latent controls.

# Day 0 Progress
Identified key datasets:
- Brain Genomics Superstruct Project (https://www.neuroinfo.org/gsp/), waiting to receive permission
- OASIS 1 (https://sites.wustl.edu/oasisbrains/home/oasis-1/)
- OASIS 2 (https://sites.wustl.edu/oasisbrains/home/oasis-2/)
- MULTI-CLARID (https://openneuro.org/datasets/ds005795/versions/1.0.0), waiting to access personality data
- NIMH Healthy Research Volunteer Dataset (https://openneuro.org/datasets/ds005752/versions/2.1.0)
- Dallas Lifespan Brain Study (https://openneuro.org/datasets/ds004856/versions/1.2.0)
- 7T fMRI Resting-state Dataset (https://openneuro.org/datasets/ds005747/versions/1.2.1), only age and sex information available
- Resting State Perfusion in Healthy Aging (https://openneuro.org/datasets/ds000240/versions/2.0.0)
- Exploring the Resting State Neural Activity of Monolinguals and Late and Early Bilinguals (https://openneuro.org/datasets/ds001747/versions/1.1.0)
- Resting state with closed eyes for patients with depression and healthy participants (https://openneuro.org/datasets/ds002748/versions/1.0.5)
- A high resolution 7-Tesla resting-state fMRI test-retest dataset with cognitive and physiological measures (https://openneuro.org/datasets/ds001168/versions/1.0.1)
- rs-fMRI for Healthy, Parkinson's with normal cognition, and Parkison's with mild cognitive impairment (https://openneuro.org/datasets/ds005892/versions/1.0.0)
- Human Connectome Project, can directly use on AWS S3!

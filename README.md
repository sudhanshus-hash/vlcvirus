# VLCvirus: Subunit Vaccine Candidates Against Lung Cancer Viruses

Welcome to the official repository and documentation overview for the **VLCvirus**, a comprehensive web resource dedicated to the in-silico identification of subunit vaccine candidates against major lung cancer-causing oncogenic viruses. This resource provides researchers with systematically identified, highly immunogenic, and safe epitope-based vaccine candidates to aid in lung cancer immunotherapeutics.

**Web Server:** [https://webs.iiitd.edu.in/raghava/vlcvirus/](https://webs.iiitd.edu.in/raghava/vlcvirus/)

## Citation

Lathwal, A., Kumar, R., & Raghava, G. P. S. (2021). 
**In-silico identification of subunit vaccine candidates against lung cancer-associated oncogenic viruses.** *Computers in Biology and Medicine*, 130, 104215. 
[https://doi.org/10.1016/j.compbiomed.2021.104215](https://doi.org/10.1016/j.compbiomed.2021.104215)

This tool and dataset is also available on Zenodo at https://doi.org/10.5281/zenodo.20067189

## About the Database

VLCvirus provides computationally validated, epitope-based subunit vaccine candidates utilizing a reverse vaccinology approach. The database focuses on predicting specific pathogenic components capable of inducing both humoral and cell-mediated immunity without triggering a self-immune response. 

The database integrates data from:
* **9 Oncogenic Virus Species:** Including HPV, HBV, RSV, STLV, BLV, HTLV, EBV, Measles virus, and JC virus.
* **Reference Proteomes:** Systematically analyzed 945 proteins from 100 standard viral reference proteomes extracted via UniProt.

## Key Features

### Comprehensive Dataset
* **125 best antigenic epitopes** identified with predicted B-cell, T-cell, and/or MHC-binding capability and vaccine adjuvant potential.
* Filtered strictly against 1,000 reference normal human proteomes to avoid self-tolerance and potential autoimmune reactions.

### Built-in Prediction & Analysis Tools
* **Immune Epitope Prediction:** Integration of LBTope (B-cell), CTLPred (T-cell), and VaxinPAD (Vaccine Adjuvants).
* **MHC Binding & Cytokine Analysis:** Uses ProPred-I, ProPred, IL4pred, IL-10pred, and IFNepitope to pinpoint epitopes that act as MHC binders and induce crucial immune-boosting cytokines.
* **Toxicity & Allergenicity:** Filtering safe candidates utilizing ToxinPred, AllerTOP, and AllerCatPro.
* **Structural Annotation:** 3D structures of the candidate antigenic epitopes modeled using PEPstrMOD.



## Overview

VLCvirus is organized to offer robust data exploration and structural insights:
1.  **Antigenic Epitopes:** A catalog of strictly vetted ninemer (9-mer) peptides acting as ideal vaccine candidates.
2.  **MHC I & II Binders:** Promiscuous epitopes with binding affinity to 15 MHC-I and 49 MHC-II human HLA alleles.
3.  **Cytokine Inducers:** Profiles of 32 top epitopes with high IL-4 and IFN-gamma inducing potential.
4.  **Structural Properties:** Explore 3D structures of top epitopes.
5.  **Promiscuous & Conserved Epitopes:** Mapped across multiple viral strains to support heterologous (cross-strain) immunity.



## Applications

* **Vaccine Design:** Rapid shortlisting of peptide candidates for clinical trials, cutting down experimental cost and time.
* **Immunotherapy Development:** Discovering non-toxic, non-allergenic peptides to assist in targeted treatments and advanced-stage lung cancer immunotherapy.
* **Cross-Strain Prophylaxis:** Identifying immune-dominant, conserved epitopes capable of offering mass-scale prophylactic immunity across distinct populations.

## Contact & Authors

**Prof. G.P.S. Raghava** raghava@iiitd.ac.in  
Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT-Delhi), New Delhi, India.

## License

This resource is freely accessible to the scientific community.

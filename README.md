# Ethanolamine metabolism in *E. coli*

This repository contains the models and data used for investigating ethanolamine and glycerol co-metabolism in *Escherichia coli*:
- genome-scale model used for flux balance analysis
- isotopic model used for <sup>13</sup>C metabolic flux analysis

## Genome-scale model for Flux Balance Analysis

The genome-scale model iDJ1518 is provided in JSON (`.json`) and SBML (`.xml`) formats in the folder `genome-scale_model/model` and is also available in [Biomodels database](https://www.ebi.ac.uk/biomodels/) under identifier [MODEL2403010003](https://www.ebi.ac.uk/biomodels/MODEL2403010003). The model is decribed in the publication, and the code used to perform flux balance analysis and flux variability analysis can be found in the associated Jupyter notebook [genome-scale_model/ethanolamine_metabolism.ipynb](https://github.com/MetaSys-LISBP/ethanolamine_metabolism/blob/main/genome-scale_model/ethanolamine_metabolism.ipynb).

## Isotopic model for <sup>13</sup>C-Fluxomics 

The dynamic <sup>13</sup>C-flux model can be used to simulate the labeling and metabolite dynamics of intracellular and extracellular metabolite concentrations. The model is provided in COPASI (`.cps`) and SBML (`.xml`) formats in the folder `isotopic_model/model` and is also available in [Biomodels database](https://www.ebi.ac.uk/biomodels/) under identifier [MODEL2403010002](https://www.ebi.ac.uk/biomodels/MODEL2403010002). Detailed description of the model can be found in [isotopic_model/model_documentation.pdf](https://github.com/MetaSys-LISBP/ethanolamine_metabolism/blob/main/isotopic_model/model_documentation.pdf).

This model can also be used to calculate fluxes by fitting time-course measurements of the concentration of
cells and extracellular (unlabeled and labeled) substrates and products, as detailed in the publication. The data used to calculate fluxes in each 
biological replicate are provided in the folder `isotopic_model/data`.

## How to cite
Publication in preparation.

## Authors
Pierre Millard, Denis Jallet

## Contact
:email: pierre.millard@insa-toulouse.fr
:email: denis.jallet@insa-toulouse.fr
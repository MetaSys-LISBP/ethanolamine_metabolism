# Ethanolamine metabolism *E. coli*

This repository contains the model and data used for:
- <sup>13</sup>C metabolic flux analysis of ethanolamine and glycerol co-metabolism in *Escherichia coli*, as detailed in the publication.

## Isotopic model for <sup>13</sup>C-fluxomics 

The dynamic <sup>13</sup>C-flux model can be used to simulate the labeling and metabolite dynamics of intracellular and extracellular metabolite concentrations. The model is provided in COPASI (`.cps`) and SBML (`.xml`) formats in the folder `isotopic_model/model` and is also available in [Biomodels database](https://www.ebi.ac.uk/biomodels/) under identifier [MODEL2403010002](https://www.ebi.ac.uk/biomodels/MODEL2403010002). Detailed description of the model can be found in [isotopic_model/Model_documentation.pdf](https://github.com/MetaSys-LISBP/ethanolamine_metabolism/blob/main/isotopic_model/Model_documentation.pdf).

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
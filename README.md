# 27410 - Group assignment - Group 6 - Production of the anti-malaria drug artemisinin in _Bacillus Subtilis_

## Project summary
This project aimed to produce the artemisinin precursor, dihydroartemisinic acid (DHAA), for future large-scale production of an anti-malarial drug, utilising _B. subtilis_ as a cell factory. Seven relevant heterologous genes were incorporated into the existing GSM model iYO844, and the maximum theoretical yield of DHAA utilising different carbon sources was calculated. Furthermore, a phenotypic phase plane analysis was conducted to investigate the correlation between biomass production, oxygen consumption, and production of DHAA. FSEOF analysis was applied to investigate up- or downregulation targets to optimise production, and DFBA was conducted to investigate how the production of DHAA develops over time in a batch cultivation. These analyses showed that production of DHAA was possible in _B. subtilis_, and several genes for up- and downregulation for further optimization was suggested. Other optimization strategies like OptGene, OptKnock, and co-factor swapping were attempted, but no results were obtained.

## Project overview
The text of the report is contained in the file called [Report.ipynb](Report.ipynb). The code for the results obtained in the analyses are contained in different files across the repository. The project code should be read in the following order:
[0_memote_analysis.ipynb](0_memote_analysis.ipynb)  - contains the memote analyses of four GSM models for _Bacillus subtilis_
[1_incorporation_of_heterologous_genes.ipynb](1_incorporation_of_heterologous_genes.ipynb) - contains the original GSM model and the modifications made to it
[2_maximum_theoretical_yield.ipynb](2_maximum_theoretical_yield.ipynb) - contains maximum theoretical yield investigations based on varying carbon sources
[3_phenotypic_phase_planes.ipynb](3_phenotypic_phase_planes.ipynb) - contains PPP analyses on the correlation between growth, oxygen uptake and the production of DHAA
[4_FSEOF_analysis.ipynb](4_FSEOF_analysis.ipynb) - contains investigations into targets for up- and downregulation
[5_DFBA.ipynb](5_DFBA.ipynb) - contains batch cultivation simulations using dynamic flux balance analysis
[6_Optimisation_target_analysis.ipynb](6_Optimisation_target_analysis.ipynb) - contains model optimization attempts using OptGene and OptKnock
[7_Co-factor_swap.ipynb](7_Co-factor_swap.ipynb) - contains a co-factor-swapping optimization analysis
The figures from the analyses are located in the "figures" folder, the original and modified models used in this work are located in the "data" folder, and the files for the Memote analyses are located in the "memote" folder.

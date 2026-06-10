# HTDaA SLR
Systematic Literature Review of Robotic Deconstruction

create a conda environment, require an api key from scopus, web of science and ieee, set environment variables according to instruction from each database. 

Python 3.10 with requirements.txt

### Notebooks

The first notebook, 'HTDaA_SLR_search.ipynb' acquires results from 3 databases for 3 different topic sets, 
* robotic deconstruction of the built environment
* robotic disassembly (in the context of manufacturing and production)
* robotic construction 

This notebook also collates different database responses, eliminating duplicate entries, and preparing the subsequent combined responses for screening, done manually, by inspection of titles, abstracts and finally the text itself. 

The second notebook 'HTDaA_SLR_analysis_biblio.ipynb' uses metadata across the topic sets for a series of plots, with the goal of identifying publishing patterns. 

### Data

Search results are locatd in HTDaA_SLR_data/
Screening results are located in HTDaA_SLR_screening/





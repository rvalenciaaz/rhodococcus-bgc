# rhodococcus-bgc

This repository contains the main scripts used in the article 

Agustina Undabarrena, Ricardo Valencia, Andrés Cumsille, Leonardo Zamora-Leiva, Eduardo Castro-Nallar, Francisco Barona-Gomez; Beatriz Cámara. Rhodococcus comparative genomics reveals a phylogenomic-dependent NRPS distribution: insights into BGC connection to an orphan metabolite.
1. Simple filtering of duplicate labels
2. Filtering of NRPS BGCs by NRPS features, such as number of adenylation domains
3. Checking BGCs against ANI information
4. Generation of network communities using the Louvain algorithm (python-louvain package)

Also there are two additional scripts for metadata extraction of a particular GCF, and a previsualization of the BGC network using the bokeh and graphviz packages in Python.

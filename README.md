# Ontology Modeling for Decentralized Household Energy Systems
With the spirit of reproducible research, this repository includes a complete collection of codes required to generate the results and diagrams presented in the paper:

> J. Wu, F. Orlandi, D. O'Sullivan, S. Dev, Ontology Modeling for Decentralized Household Energy Systems, *IEEE International Conference on Smart Energy Systems and Technologies (SEST)*, 2021.

## Details
- `ontoEnergy/ontoEnergy.ipynb` contains script converting tabular data into the rdf data and the coding work for figures shown in the paper. 
- `triples/individuals.owl` is a complete result of triples created by ontology modeling on CoSSMic dataset data fields. To identify the relationship between individuals implied by the data fields. We manually defined the vocabularies and named the individuals based on the CoSSMic documentation on the data fields. 
- `triples/data.ttl` contains a complete set of triples produced by `ontoEnergy/ontoEnergy.ipynb`.

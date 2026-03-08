# Clustering-Phenotype-and-identify-duplications-in-HDF-algorithm
Exploring unsupervised learning approaches to identify duplicate or highly similar phenotype algorithms based on clinical code lists.
This repository explores unsupervised machine learning approaches to identify duplicate or highly similar phenotype algorithms used in electronic health record (EHR) research.

Phenotype libraries such as the HDR UK Phenotype Library and OpenCodelists contain large collections of algorithms that define diseases or clinical conditions using sets of clinical codes (e.g., SNOMED CT, ICD). However, many of these algorithms are highly overlapping or exact duplicates, making it difficult for researchers to understand how they differ.

The goal of this project is to develop methods to:

  quantify similarity between phenotype algorithms based on their code sets
  identify exact or near duplicate algorithms
  group related algorithms using clustering approaches
  help researchers understand differences between algorithms

Initial exploration focuses on similarity metrics- Jaccard similarity and unsupervised learning methods to cluster phenotype algorithms based on their associated clinical codes.

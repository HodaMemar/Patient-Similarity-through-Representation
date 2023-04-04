# A Study into Patient Similarity through Representation Learning from Medical Records
 


![Fig_1_black-white](https://user-images.githubusercontent.com/66674325/229862689-6c7086a8-603a-4dad-b450-657ebfb5b133.jpg)


**Citing**


```bibtex
@article{Memarzadeh2022,
abstract = {Patient similarity assessment, which identifies patients similar to a given patient, is a fundamental component of many secondary uses of medical data. The assessment can be performed using electronic medical records (EMRs). Patient similarity measurement requires converting heterogeneous EMRs into comparable formats to calculate distance. This study presents a new data representation method for EMRs that considers the information in clinical narratives. To address the limitations of previous approaches in handling complex parts of EMR data, an unsupervised manner is proposed for building a patient representation, which integrates unstructured and structured data extracted from patients' EMRs. We employed a tree structure to model the extracted data that capture the temporal relations of multiple medical events from EMR. We processed clinical notes to extract medical concepts using Python libraries such as MedspaCy and ScispaCy and mapped entities to the Unified Medical Language System (UMLS). To capture temporal aspects of the extracted events, we developed two new relabeling methods for the non-leaf nodes of the tree. To create an embedding vector for each patient, we traversed the tree to generate sequences that the Doc2vec algorithm would use. The comprehensive evaluation of the proposed method for patient similarity and mortality prediction tasks demonstrated that our proposed model leads to lower mean-squared error (MSE), higher precision, and normalized discounted cumulative gain (NDCG) relative to baselines.},
author = {Memarzadeh, Hoda and Ghadiri, Nasser and Samwald, Matthias and {Lotfi Shahreza}, Maryam},
doi = {10.1007/s10115-022-01740-2},
issn = {0219-3116},
journal = {Knowledge and Information Systems},
number = {12},
pages = {3293--3324},
title = {{A study into patient similarity through representation learning from medical records}},
url = {https://doi.org/10.1007/s10115-022-01740-2},
volume = {64},
year = {2022}
}

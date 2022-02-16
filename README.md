# MedCAT Tutorials

## Introductory tutorials

In this tutorial, we will walk you through each stage of a basic MedCAT project. The blog posts are there to tell a story and explain why several steps or processes which we have decided to take are necessary. While the Jupyter Notebooks are for a hands-on experience building and training your MedCAT models for information extraction tasks.

| Part | Title                                                                       | Google Colab                                                                       | Blog Post |
| ---- |-----------------------------------------------------------------------------|------------------------------------------------------------------------------------|-----------|
| 1    | Introduction                                                                | -                                                                                  | [TDS](https://towardsdatascience.com/medcat-introduction-analyzing-electronic-health-records-e1c420afa13a)         |
| 2    | Data set Preparation and Basic Statistics                                   | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/introductory/Part_2_Dataset_Analysis_and_Preparation.ipynb) | [TDS](https://towardsdatascience.com/medcat-dataset-analysis-and-preparation-be8bc910bd6d)         |
| 3.1  | Building a new Concept Database (CDB) and Vocabulary (Vocab)                | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/introductory/Part_3_1_Building_a_Concept_Database_and_Vocabulary.ipynb) | [TDS](https://towardsdatascience.com/medcat-extracting-diseases-from-electronic-health-records-f53c45b3d1c1)         |
| 3.2  | Unsupervised training and NER+L                                             | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/introductory/Part_3_2_Extracting_Diseases_from_Electronic_Health_Records.ipynb) | [TDS](https://towardsdatascience.com/medcat-extracting-diseases-from-electronic-health-records-f53c45b3d1c1)         |
| 4.1  | Creating a tokenizer model (huggingface) and embeddings for MetaAnnotations | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/introductory/Part_4_1_ByteLevelBPETokenizer_and_Embeddings.ipynb) | -         |
| 4.2  | Supervised training and fine-tuning + Meta-annotations                      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/introductory/Part_4_2_Supervised_Training_and_Meta_annotations.ipynb) | -         |
| 4.3  | Annotating documents with the full MedCAT pipeline with MetaAnnotations     | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/introductory/Part_4_3_Annotating_documents_with_the_full_MedCAT_pipeline_with_MetaAnnotations.ipynb) | -         |
| 5    | Analysing the results                                                       | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/introductory/Part_5_Prevalence_of_Physical_and_Mental_Diseases.ipynb) | [TDS](https://towardsdatascience.com/prevalence-of-physical-and-mental-diseases-450c0f4f5851)         |


## Specialised tutorials

These tutorials expand upon specific aspects of the topics covered across the introductory tutorials. If there is anything in particular you would like us to cover in the future, let us know!

| Part | Title                                                             | Google Colab                                                                                 |
| ---- |-------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| -    |Working with SNOMED CT and building a custom Concept Database (CDB)| [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CogStack/MedCATtutorials/blob/main/notebooks/specialised/Preprocessing_SNOMED_CT.ipynb)|

# Development

Make sure `jq` is installed and install the pre-commit hook by running:
```
git config --local core.hooksPath git-config/hooks
```
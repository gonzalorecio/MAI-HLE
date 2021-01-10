# MAI-HLE
Master in Artificial Intelligence - UPC
Human Language Engineering Final Project

## **ACL-BioNLP'19 - MEDIQA 2019 Shared Task**
#### Authors: Gonzalo Recio and Jana Reventós 

The **MEDIQA 2019 Challenge** aims to attract further research efforts in Natural Language Inference (NLI), Recognizing Question Entailment (RQE), and their applications in medical Question Answering (QA). 

In this repository we focus on the implementation of the **Task 3: Question and Answering**.
The **main objective** of this task is to filter and improve the ranking of automatically retrieved answers generated in the QA CHiQA system (https://chiqa.nlm.nih.gov/). 
CHiQA is an experimental AI system that is learning how to answer health-related questions using reliable sources for patients.

## Main requisites
```
pip install torch
pip install transformers     (for BERT models)
pip install allennlp         (for ELMo models)
````

## Code

All needed code for training the models can be found in `Models.ipynb` (main notebook). `Preprocessing.ipynb` contains preprocessing, testing and helper code snippets.

## Model weights

Model weights of our models (both BERT-based and ELMo-based) can be found [here](https://drive.google.com/drive/folders/11JbGwQ7jNbWRN5EADHqA4kPcio0whI_Q?usp=sharing).


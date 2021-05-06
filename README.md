# Using Confidential Data for NMT Domain Adaptation

This is the page for the datasets used for the paper _Using Confidential Data for NMT Domain Adaptation_.
All the original parallel corpora are from [OPUS](https://opus.nlpl.eu/).

We chose **EMEA**, **GNOME** and **JRC-Acquis** domains for German to English. 



## Description of datasets


1. `\full_sent_datasets` :
    - Full sentence training, validation and test set. 
    
2. `\phrase_pairs` :
    - Extracted phrase pairs with max length 4.
    - After shuffling and sub-sampling with 50%. 

3. `\original_documents` :
    - In order to simulate our scenario better, we obtain the datasets by documents.
    We also provide the documents used to consist of our datasets.
    - All documents are named sequentially from the number 1.
    - Currently, JRC is not online but it will be uploaded soon.


### Statistics of datasets


- Full sentence datasets

Type |  Sentences 
---|---
Train | 10k
Validation | 150
Test | 2k


## References/Credits
Please cite the following paper if you use the code and of course thanks for that!

* Sohyung K., Bisazza A., Turkmen F., **Using Confidential Data for Domain Adaptation of Neural Machine Translation**, Third Workshop on Privacy in Natural Language Processing (PrivateNLP) 2021, Colocated with NAACL 2021  (To Appear).

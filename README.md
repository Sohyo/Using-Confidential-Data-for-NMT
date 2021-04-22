# Using Confidential Data for NMT Domain Adaptation

 
All the original parallel corpora are from [OPUS](https://opus.nlpl.eu/).

We chose **EMEA**, **GNOME** and **JRC-Acquis** domains for German to English. 


##

## Quick explanation for datasets

1. `\full_sent_datasets` :
    - Full sentence training, validation and test set. 
    
2. `\phrase_pairs`:
    - Extracted phrase pairs with max length 4.
    - After shuffling and sub-sampling with 50%. 

3. `\original_documents` :
    - In order to simulate our scenario better, we obtain the datasets by documents.
    We also provide the documents used to consist of our datasets.


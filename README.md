# aiopenlab_nlp
de-identification of precedent data in AI HUB 

# details of source code
- Augmentation.ipynb
  - The functions for augmenting pseudo-labeled data(law domain) by using Easy Data Augmentation(random deletion, random swap)
  - This method solve the data imbalance problem that Naver NER dataset is 7 times more than pseudu-labeled law dataset

- ETRI_API.ipynb
  - The functions to make pseudo-labeled data by using ETRI NER api
 
- Exact_matching+rule_LBox_precedents_data.ipynb
  - The functions to make pseudo-labeled data by using NTIS named entity dictionary(private) and LBox dataset

- Exact_matching_NTIS_dict.ipynb
   - The functions to make pseudo-labeled data by using NTIS name entity dictionary(private)
 
- KoBERT-NER-master
   - I used KoBERT+ CRF source code from "https://github.com/monologg/KoBERT-NER"

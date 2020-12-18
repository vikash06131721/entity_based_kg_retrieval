# entity_based_kg_retrieval
Code repository for paper Entity Based Knowledge Graph Information Retrieval For Biomedical Articles
Please follow the following steps to finetune the NER model:
1. Download the biobert model from https://github.com/dmis-lab/biobert
2. Convert to pytorch_format using the notebook tf_to_pytorch_wt.ipynb
3. Change the paths accordingly in parameters.py
4. Make sure to download bionlp13cg-iob data set for training and testing from https://github.com/cambridgeltl/MTL-Bioinformatics-2016/blob/master/data/
5. python new_train.py


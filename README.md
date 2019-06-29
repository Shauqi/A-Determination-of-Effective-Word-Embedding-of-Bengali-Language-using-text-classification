# A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification
Different target Natural Language Processing (NLP) tasks demand for pretrained semantic embedding of words also having syntactic considerations. In general, these tasks are Part of Speech (PoS) tagging, Opinion Mining, Named Entity Recognition, Textual Entailment, Semantic Role Tagging, Conference Resolution etc.

Steps to follow:
1. Download 40k Bengali News Dataset from Kaggle. Link: https://www.kaggle.com/zshujon/40k-bangla-newspaper-article
2. Preprocess the dataset using https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/Preprocessing%20of%20Bengali%20Text.ipynb. For preprocessing following file is needed: https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/stopwords-bn.json. For ELMo embedding we have to create a vocabulary file. To create vocabulary file from Bangla preprocessed dataset use this link: https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/Creating%20Vocabulary%20File%20for%20ELMo.ipynb. The vocabulary file can be found in this link: https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/vocab.txt
3. Convert the texts into vectors using different embedding techniques and classify them with different architectures:
    1. FastText + CNN - https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/FastText%20%2B%20CNN.ipynb
    2. FastText + CNN + LSTM - https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/FastText%20%2B%20CNN%20%2B%20LSTM.ipynb
    3. FastText + Bi Directional LSTM - https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/FastText%20%2B%20Bi-Directional%20LSTM.ipynb
    


Miscellaneous:
You can plot fasttext word vectors using t-SNE plot from this link: https://github.com/Shauqi/A-Determination-of-Effective-Word-Embedding-of-Bengali-Language-using-text-classification/blob/master/t-SNE%20Plot%20of%20FastText%20Embedding.ipynb

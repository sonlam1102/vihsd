# ViHSD-Vietnamese Hate Speech Detection dataset
This dataset is used for hate speech detection on Vietnamese language.       

Please contact this email: sonlt@uit.edu.vn (Mr. Son Thanh Luu) for the dataset.  

This dataset contains 33,400 annotated comments used for hate speech detection on social network sites.  
Label: CLEAN (non hate), OFFENSIVE and HATE

To understand more about the dataset, please read this paper: [A Large-Scale Dataset for Hate Speech Detection on Vietnamese Social Media Texts](https://arxiv.org/abs/2103.11528)

The source codes are written in python with Jupyter notebook format. It is easy to run by Jupyter notebook or Google colab. 

- The deep neural networks includes: TextCNN and GRU. Code stored in file: _ViHSD_DNN.jpynb_    
- The transformer models includes: m-bert cased, m-bert uncased, xlm-r, and DistilBERT. Code stored in file: _ViHSD_multilingual_Transformers.ipynb_     

**Please cite the following paper if you use this dataset:**

```
@InProceedings{10.1007/978-3-030-79457-6_35,
author="Luu, Son T.
and Nguyen, Kiet Van
and Nguyen, Ngan Luu-Thuy",
editor="Fujita, Hamido
and Selamat, Ali
and Lin, Jerry Chun-Wei
and Ali, Moonis",
title="A Large-Scale Dataset for Hate Speech Detection on Vietnamese Social Media Texts",
booktitle="Advances and Trends in Artificial Intelligence. Artificial Intelligence Practices",
year="2021",
publisher="Springer International Publishing",
address="Cham",
pages="415--426",
abstract="In recent years, Vietnam witnesses the mass development of social network users on different social platforms such as Facebook, Youtube, Instagram, and Tiktok. On social media, hate speech has become a critical problem for social network users. To solve this problem, we introduce the ViHSD - a human-annotated dataset for automatically detecting hate speech on the social network. This dataset contains over 30,000 comments, each comment in the dataset has one of three labels: CLEAN, OFFENSIVE, or HATE. Besides, we introduce the data creation process for annotating and evaluating the quality of the dataset. Finally, we evaluate the dataset by deep learning and transformer models.",
isbn="978-3-030-79457-6"
}
```

**_Please note that this dataset is used only for research purposes**

# ViHSD-Vietnamese Hate Speech Detection dataset
This dataset is used for hate speech detection on Vietnamese language.   

Please contact this email: sonlt@uit.edu.vn (Mr. Son Thanh Luu) for the data    

This dataset contains 33,400 annotated comments used for hate speech detection on social network sites.  
Label: CLEAN (non hate), OFFENSIVE and HATE

To understand more about the dataset, please read this paper: https://arxiv.org/abs/2103.11528

The source codes are written in python with Jupyter notebook format. It is easy to run by Jupyter notebook or Google colab. 

- The deep neural networks includes: TextCNN and GRU. Code stored in file: _ViHSD_DNN.jpynb_    
- The transformer models includes: m-bert cased, m-bert uncased, xlm-r, and DistilBERT. Code stored in file: _ViHSD_multilingual_Transformers.ipynb_    

**Please cite the following paper if you use this dataset:**

Luu S.T., Nguyen K.V., Nguyen N.LT. (2021) A Large-Scale Dataset for Hate Speech Detection on Vietnamese Social Media Texts. In: Fujita H., Selamat A., Lin J.CW., Ali M. (eds) Advances and Trends in Artificial Intelligence. Artificial Intelligence Practices. IEA/AIE 2021. Lecture Notes in Computer Science, vol 12798. Springer, Cham. https://doi.org/10.1007/978-3-030-79457-6_35

**_Please note that this dataset is used only for research purposes only_**

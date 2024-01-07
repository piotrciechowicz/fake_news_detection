# Fake news detection  

## About project

Fake News Classification using deep learning method in PyTorch.

## Datasets

Dataset comes from kaggle.com.

### WELFake

<img width="1029" alt="Zrzut ekranu 2023-04-17 o 20 19 56" src="https://user-images.githubusercontent.com/101282458/232575677-06b0019c-55c6-4ffc-8739-feafcb286165.png">

https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

### Fake & Real

<img width="1029" alt="Zrzut ekranu 2023-04-17 o 19 09 21" src="https://user-images.githubusercontent.com/101282458/232559366-ddf5b233-33ef-4d72-9a78-aef188e5251e.png">

https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?select=True.csv

### Fake news net

<img width="1029" alt="Zrzut ekranu 2023-04-17 o 19 23 38" src="https://user-images.githubusercontent.com/101282458/232562568-aebc3925-e960-4a00-b644-1982a32d48b5.png">

https://www.kaggle.com/datasets/algord/fake-news

# Model

Classification model is based on Logistic Regression in PyTorch library. To find the best hyperparameters for logistic regression Optuna was used and the model was evaluated using k-stratified fold Cross Validation that uses train, test and validation part of the dataset.

Model performance was compared with and without cutting "stopwords" and cutting lemmatization.

To reach better results more complex neutral network was implemented for each datasets.

Similar news were found using cosine distance in vector space in all three datasets.

# Libraries

- numpy
- pandas
- matplotlib
- pandas-profiling
- pathlib
- wordcloud
- nltk
- sentence_transformers
- torch
- optuna

# Contact

👋  piotr.ciechowicz@gmail.com




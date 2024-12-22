# Text-classification
Text classification using wide range of ML/DL models


## Dataset
* [news-data](https://huggingface.co/datasets/okite97/news-data)

## Models

### Metric
* F1-score


### Vectorization

* BoW (0.8610), tf-idf (0.8567)
* fasttext (0.8808)
* ELMo (0.8761)
* BERT (0.8892)


### Classification
* logistic regression


## Comments
* The gap between non-contextualized embeddings and contextualized embeddings turned out to be weak due to the characteristics of the data
* Samples can be classified using BoW-like things (ex. between sports and politics classes)


## Future work
* Fine-tuning lstm/bert (full tuning, parameter-efficient fine tuning (peft) -- ex. lora or freezing some layers)
* Train lstm/transformer using any vectorization models
* Another way to feature aggregation: concatenating (Title, Excerpt) instead of averaging


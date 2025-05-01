# Product-Review-Sentiment-Analysis


### SETUP
dockerfile
docker build -t sentiment-analysis .
docker run -p 8888:8888 -v C:/Users/User/Workspaces/01-Projects/Product-Review-Sentiment-Analysis:/app sentiment-analysis

### 1. Text pre-processing
lower case only, no punctuation
no stop words

Tokenization
Bag of words 

Transformation/ Vectorization
Lemmatisation| Stemming

## Dataset Citation

> Hou, Y., Li, J., He, Z., Yan, A., Chen, X., & McAuley, J. (2023). *Bridging Language and Items for Retrieval and Recommendation*. arXiv preprint [arXiv link](https://arxiv.org/abs/2305.11999).

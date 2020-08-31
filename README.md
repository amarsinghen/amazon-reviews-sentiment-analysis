# amazon-reviews-sentiment-analysis using NLP
amazon-reviews-sentiment-analysis

Please see the jupyter notebooks. They are very self-explanatory.

Results Summary:
| No. | Notebook Name | Description | Embedding Type | Val Loss | Val Acc |
| --- | ------------- | ----------- | -------------- | -------- | ------- |
| 1 | amazon_reviews_sentiment_analysis_additional_data_preprocessing.ipynb | Data Preprocessing without Stemming and Lemmatization. NLTK Stopwords. | Custom keras embedding layer | 0.1685 | 0.9366 | 
| 2 | amazon_reviews_sentiment_analysis_basic_model_glove_embedding.ipynb | Very basic data preprocessing | GLOVE Embedding | 0.1702 | 0.9386 |
| 3 | amazon_reviews_sentiment_analysis_data_model_improved.ipynb | Most comprehensive data preprocessing and custom stopwords list | Custom Keras embedding layer | 0.1438 | 0.9483 |
| 4 | amazon_reviews_sentiment_analysis_fasttext_embedding.ipynb | Most comprehensive data preprocessing and custom stopwords list | Fasttext embedding layer | 0.1870 | 0.9366 |
| 5 | amazon_reviews_sentiment_analysis_lstm_basic_datapreprocessing.ipynb |  Very basic data preprocessing | Custom keras embedding layer | 0.1561 | 0.9444 |


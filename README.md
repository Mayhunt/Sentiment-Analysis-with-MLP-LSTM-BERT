# Sentiment-Analysis-with-MLP-LSTM-BERT  [:+1: VS :-1:]
:page_with_curl: IMDB Dataset of Movie Reviews from : https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews </br>
:page_with_curl: My Coding : https://colab.research.google.com/drive/1Hm4zCt6TelenfNEUiiqnSc2m3kv40vmA?usp=sharing

![ภาพหน้าจอ (27)](https://user-images.githubusercontent.com/99718534/188877958-a8c7afc8-1fee-4e5f-8c00-7f2f771e252f.png)

## :triangular_flag_on_post: Method
### - __Data Visualization__ :chart_with_upwards_trend:
### - __Data Prepocessing__ :black_nib:
  1. *__Removing unnecessary marks in data__* such as < > , \ . ! ? : ()
  2. *__Capitalization to lowercase__*
  3. *__Expand Contraction__*
  4. *__Tokenization__* : Tokenization is the process of tokenizing or splitting a string, text into a list of tokens. One can think of a token as parts like a word is a                           token in a sentence, and a sentence is a token in a paragraph.
  5. *__Removing stopwords in data__* : Stopwords are words that do not contribute to the meaning of a sentence.
  6. *__Stemming__* : having -> hav
  7. *__Lemmatization__* : having -> have
  8. *__Word embedding__* :   Word Embeddings are a numerical vector representation of the text in the corpus that maps each word in the corpus vocabulary to a set of                                 real valued vectors, a dense vector of floating point values, in a pre-defined N-dimensional space. Ex. train -> [0.2, 0.8, 0.4]
### - __Algorithms__ :computer:
  1. *__MLP (Multilayer Perceptron)__*
  2. *__LSTM (Long short-term memory)__*
  3. *__BERT (Bidirectional Encoder Representations from Transformers)__*

## Conclusion :white_check_mark:
  The models predict classes of sentiment in the test set with high accuracy over 85%. MLP achieved accuracy of 89%, LSTM achieved accuracy of 87% and BERT achieved accuracy of 95%. BERT achieved the highest accuracy in this case. So, this state-of-the-art language model can understand natural language and context of the sentence in the IMDB dataset and can classify the classes of sentiment in each review fairly well. By the way, each algorithm has its advantages and is suitable in different work and dataset.

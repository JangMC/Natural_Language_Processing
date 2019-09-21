# Natural_Language_Processing
NLP projects in Python

<b><i> Language_Models.ipynb </b></i>

In the Language_Models file is a 2x2 factorial design with pre-trained word vectors (glove.6B.50d and glove.twitter.27B.50d) and vocabulary sizes (10,000 and 40,000) as the two experimental factors for a language model. A recurrent neural network model is created based on 1000 movie reviews (500 positive and 500 negative reviews). The 2x2 experiment revealed similar accuracy regardless of the pre-trained word vector or vocabulary size.

Pre-trained word vectors can be particularly helpful in quickly classifying complaints, reviews, etc. Using pre-trained word vectors that leverage different sources, such as Twitter compared to Wikipedia, yielded a slightly different, but yet comparable result. Taking a slightly bigger subset of words also worked better with Twitter as the corpus rather than the slightly bigger subset of words that leverages Wikipedia. It seems that people don’t need a lot of different words to express complaints and most complaints can be identified in meaningful ways with about 65% - 68.5% accuracy.


<b><i> NLP_Learned_Vs_PreTrained_WordEmbeddings.ipynb </b></i>

In the NLP_Learned_Vs_PreTrained_WordEmbeddings file different models were explored using both a learned and a pre-trained word vector (glove.6B.100d). Models included:

- dense
- convolutional
- recurrent
- gated recurrent network (GRU)
- long short-term memory (LSTM)



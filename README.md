# Sentiment-Analysis-and-Stock-Values
Sentiment analysis of economic news headlines and examining their effects on stock market changes without the full article or analysis. Awareness and click generation are important roles for business news headlines as well. The effect can be demonstrated.


### TextBlob

TextBlob is a powerful NLP library for Python. Which is built upon NLTK and provides an easy to use interface to the NLTK library. This tool can be used to perform a variety of NLP tasks ranging from parts-of-speech tagging to sentiment analysis, and language translation to text classification, but we focusing to the sentiment analysis. If we do a sentiment analysis, we actually determine a polarity value of the sentences, where the this value can be between -1 and 1. Then we label the data with the right sentiment value (positive, negative or neutral). For other tools, the polarity value may move on a different scale, so the labeling needs to adjust for these differences for further analysis.

### NLTK - Vader Lexicon

NLTK stands for Natural Language Toolkit. This toolkit is one of the most powerful NLP libraries which contains packages to make machines understand human language and reply to it with an appropriate response. Again, we focus on sentiment analysis with the SentimentIntensityAnalyzer. The polarity value of the sentences scales between -1 and 1 just like in the TextBlob. The data labeling process (positive, negative or neutral) is similar to the previous tool. We use VADER Lexicon in this section. VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media, and works well on texts from other domains.

### Recurrent Neural Network (RNN)

When we talk about traditional neural networks, all the outputs and inputs are independent of each other. But in the case of recurrent neural networks, the output from the previous steps is fed into the input of the current state.

All in all the Recurrent Neural Network - A neural network that is intentionally run multiple times, where parts of each run feed into the next run. Specifically, hidden layers from the previous run provide part of the input to the same hidden layer in the next run. Recurrent neural networks are particularly useful for evaluating sequences, so that the hidden layers can learn from previous runs of the neural network on earlier parts of the sequence.

For example, the following figure shows a recurrent neural network that runs four times. Notice that the values learned in the hidden layers from the first run become part of the input to the same hidden layers in the second run. Similarly, the values learned in the hidden layer on the second run become part of the input to the same hidden layer in the third run. In this way, the recurrent neural network gradually trains and predicts the meaning of the entire sequence rather than just the meaning of individual words.

### Bidirectional Encoder Representations from Transformers (BERT)

Unlike the traditional NLP models that follow a unidirectional approach, that is, reading the text either from left to right or right to left, BERT reads the entire sequence of words at once. BERT makes use of a Transformer which is essentially a mechanism to build relationships between the words in the dataset. In its simplest form, a BERT consists of two processing models- an encoder and a decoder. The encoder reads the input text and the decoder produces the predictions. But, because the main goal of BERT is to create pre pre-trained model, the encoder takes priority over decoder. BERT is a remarkable breakthrough in the field of NLP.

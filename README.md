# emoji-prediction

Emoji Prediction

## Goal

## Given a tweet, predict the most likely emoji that was used along with it.

### Variants

    Classification
    Emoji Embeddings

## MVPs
### Classification

    Train an embedding model (character or word) on the tweets.
    Get tweet embeddings using averaging/any other method.
    Classify tweets using KNN Naive Bayes.
    Classify tweets using simple MLP.

## Emoji Embeddings

    Train an embedding model on the tweets along with the emojis.
    Given a tweet without emoji, find its embedding (averaging of word embeddings).
    Find closest emoji to it.

## Taking it forward

    Recurrent networks Train a simple single-layer RNN with softmax activation for classification. Use the embeddings obtained from the RNN model and see how they perform with MVPs.

## Dataset

https://github.com/fvancesco/Semeval2018-Task2-Emoji-Detection/blob/master/dataset/Semeval2018-Task2-EmojiPrediction.zip?raw=true

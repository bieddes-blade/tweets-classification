# tweets-classification

Problem statement: we have a set of tweets describing a person's health condition. We want to divide the tweets into two categories based on whether they contain a message about an adverse side effect that occurred while the poster was using medication.

To solve this problem, we first use a fastText model pretrained on the raw part of the [RuDReC corpus](https://github.com/cimm-kzn/RuDReC) to initialize a matrix of embeddings, and then classify the tweets into groups using a [TextCNN](https://github.com/ShawnyXiao/TextClassification-Keras/tree/master/model/TextCNN) model.

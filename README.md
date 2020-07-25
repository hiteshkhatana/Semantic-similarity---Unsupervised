# Semantic-similarity---Unsupervised

Three basic techniques are applied for predicting semantic similarity between sentences.
1) Word embedding using keras one_hot and perceptron model with embedding layer.
2) Word embedding using dictionary of words for one_hot encoding and perceptron model with embedding layer.(I have tried this as keras one_hot donot guarantee unicity and it was giving same number to different words.)
3) Spacy pretrained model (en_core_web_lg) which contains 1 M words vector of english langauge.

->most Accurate and fastest prediction is performed by pretrained model by Spacy.

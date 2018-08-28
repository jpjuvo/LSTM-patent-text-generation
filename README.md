# Generate patent descriptions with LSTM network

This demo explores how long short-term memory (LSTM) units of a neural network can be used to generate sequence data such as text.
We try to learn the latent space of specific type of language model, patent descriptions, and train our neural network to predict the next character of a text sequence drawn from this probabilistic space.
When we apply this process iteratively, we can generate completely new patent descriptions from an initial seed phrase.

**[Run notebook](./LSTM-patent-text-generation.ipynb)**

This demo is partly modified from François Chollet, 2017 [notebook examples](https://github.com/fchollet/deep-learning-with-python-notebooks/)
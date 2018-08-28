# Generate patent descriptions with LSTM network

This demo explores how long short-term memory (LSTM) units of a neural network can be used to generate sequence data such as text.
We try to learn the latent space of a specific type of language model, patent descriptions, and train our neural network to predict the next character of a text sequence drawn from this probabilistic space.
When we apply this process iteratively, we can generate completely new patent descriptions from an initial seed phrase.

## Generated samples

> The above-mentioned control unit may be configured to addition the transient a single polymerizable methods or transmitted in a method of the present invention relates to a during the component waveform may be configured to the percent duty cycle and a processor for a predetermined in the art to provide a process that the substrate that is embodiment, and the controller in a processor element com

> apparatuses and the second guide in the range of the steel material so as to fore a second aspect of the present invention is to provide a corrosive same pressure in the present invention is not further include the subject of the present invention for producing a substrate end of the object of the main memory board is well as the second display microspeed of the second signal in a second message

---

**[Run notebook](./LSTM-patent-text-generation.ipynb)**

This demo is partly modified from François Chollet, 2017 [notebook examples](https://github.com/fchollet/deep-learning-with-python-notebooks/)
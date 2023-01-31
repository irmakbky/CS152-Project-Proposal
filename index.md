<!-- ![](https://tinypng.com/images/social/website.jpg) -->

<!-- <style>
body {
 background-image: url("https://tinypng.com/images/social/website.jpg");
}
</style> -->

<body style="background-image: url("https://tinypng.com/images/social/website.jpg")">
## Music Generation Using MIDI Data
</body>

<img width="706" alt="Screen Shot 2022-01-31 at 10 31 19 PM" src="https://user-images.githubusercontent.com/70275805/151922679-d2decf1d-687c-4162-b8fa-519ef519af07.png">

Cheng-Zhi Anna Huang (2018). [Music Transformer: Generating Music with Long-Term Structure](https://magenta.tensorflow.org/music-transformer) based on [this paper](https://arxiv.org/abs/1809.04281)

### Project Proposal

In this project, I will be training a (deep) neural network to generate new compositions. The NN will be trained on MIDI data representing compositions from different composers and/or instruments.The NN is expected to discover harmonic, rhythmic, and melodic patterns and be able to predict the next “token” in a given sequence of MIDI data.

One way to approach this will be by utilizing a language model. I will be expressing MIDI data as a sequence of words and train an existing language model that performs unsupervised learning to predict the next word in a sequence. Some popular models that can be used are transformer models like GPT-2.

As a result of training a language model to predict the next token in an input sequence, I expect this model to generate a series of predictions so that we end up with a brand new composition, hopefully inspired by certain composer styles and the musical elements found in the training data.

### Project Goals
1. Get MIDI data and train a NN for music generation
2. Get NN to predict the next token in a given MIDI file
3. Generate successive predictions to eventually produce full-length pieces
4. Experiment with different instruments/composers


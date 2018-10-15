# autoencoder
Traditional autoencoders are models (usually multilayer artificial neural networks) designed to output a reconstruction of their input. Specifically, autoencoders sequentially deconstruct input data into hidden representations, then use these representations to sequentially reconstruct outputs that resemble the originals.

The appeal of this setup is that the model learns its own definition of a “meaningful” representation based only on the data—no human-derived heuristics or labels! This approach stands in contrast to the majority of deep learning systems in production today, which rely on expensive-to-obtain labeled data (“This image is a kitten; this image is a panda.”). Alternatives to such supervised learning frameworks provide a way to benefit from a world brimming with valuable raw data.

The notebook here demonstrates the 2 different ways for performing encoding and decoding of mnist images. The first approach is the traditional approach and second approach is using convolutional nn.

### Autoencoder Architecture
![autoencoder_architecture.png](https://github.com/jaynilpatel/autoencoder/blob/master/img/ae.png )

### Convolutional Autoencoder for Mnist
![convolutional-autoencoder.png](https://github.com/jaynilpatel/autoencoder/blob/master/img/ae-conv.png)

## Result
![Output.gif](https://github.com/jaynilpatel/autoencoder/blob/master/convolutional-autoencoder/ae.gif)

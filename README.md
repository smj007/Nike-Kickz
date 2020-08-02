# Nike-Kickz
DCGAN by Radford et al. on kickz

## A deep convolutional generative adversarial network that produces images of basketball shoes

This is a colab run for producing completely artificial images or shoes through a DCGAN, based on the [blog post](https://medium.com/@connorshorten300/generating-basketball-shoes-with-dcgans-6cd72d521c01) by Dr.Connor Shorten (Github: [@CShorten](https://github.com/CShorten))

The project uses a number of shoe images, with varying colors, which a DCGAN is trained to produce custom designs. 

<!--So as a clever twist to get the bespoke dataset into a format that the DCGAN expects - a NumPy shape of (140, 45, 45, 3) - the images needed to be decomposed to their raw pixel values, and then persisted by storing them as an array in NumPy's uncompressed NPZ format. The 140 images Connor uses with both the testing and training sets combined come out to 1.6MB on disk.

<!--After training the DCGAN over a run of 10,000 iterations with fairly simple generator and discriminator models, the following progression is achieved:



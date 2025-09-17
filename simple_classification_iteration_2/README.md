### Instrument detector se3cond iteration

by Kiana Rezaee 

this model classifies musical instruments, I used kaggle's musical instrument dataset of images to train it [found here](https://www.kaggle.com/datasets/nikolasgegenava/music-instruments) as well as an unsplash random image dataset to train the noinstrument class [found here](https://www.kaggle.com/datasets/lprdosmil/unsplash-random-images-collection).

the classes I created were
noinstrument
accordion 
banjo 
drums 
flute 
guitar
violin

there are around 120-190 samples in each class

the meparameters were 60 epochs, 16 bath size and 0.001 as the learning rate

As this was the second iteration, after using the musical dataset which was clear and tested well, I decided to try and problem solve a bit on the noInstrument class. However, the previous issue of some classes being similar still caused confusion eg. violin and guitar. the most impressive feat was its ability to detect things like electric guitars as guitars or different types of drums as drums. 
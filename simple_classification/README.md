### Instrument detector

by Kiana Rezaee and Dorsa Zare

this model classifies musical instruments, we used kaggle's musical instrument dataset of images to train it [found here](https://www.kaggle.com/datasets/nikolasgegenava/music-instruments).

the classes we created are
noinstrument
accordion 
banjo 
drums 
flute 
guitar
violin

there are around 150-190 samples in each class

the parameters were 60 epochs

to achieve good performance we tried to find a dataset that was clear and test the set to ensure it did not mix different objects found in the classroom as instruments. the noinstrument class helped us create a class wherein the machine did not confuse us for instruments either. however, because we only did this class in the classroom, it is not varied enough and is confused when faced with different lighting and rooms. As we increased classes, some classes were similar and could cause confusion eg. violin and guitar. the most impressive feat was its ability to detect things like electric guitars or different types of drums as drums. 

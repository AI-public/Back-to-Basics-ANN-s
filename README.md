
# Deeper-into-Basics : The CNN Autoencoder

Dissection of a simpleCNN autoencoder, mostly as basis for further work 


usually :
The "bottleneck" autoencoder is used to  compress data by finding 
a  set of non linear Principal Components.
Hence, 3 parts are distinguished:
1- the input : information to be compressed
2- the middle layer : compressed information
3- the output : estimation of information in the input using data from the middle layer (compressed)
And thats it!


However, the ideas are WAY more interesting than the 3 points just mentionned.

Lets discover some of the hidden histories of the basic CNN-Autoencoder


to begin with we will be using a simple CNN autoencoder that works with handwritten numbers.
The autoencoder is already trained , the file xxx.hdf5 contains all the weights
and biases, required by the sequential model called " Autoencoder".






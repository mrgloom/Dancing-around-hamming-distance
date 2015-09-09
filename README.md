# Dancing-around-hamming-distance

Collection of various code snippets using hamming distance for image retrival.

1. http://www.cs.toronto.edu/~norouzi/research/mlh/ Minimal Loss Hashing for Compact Binary Codes.
2. http://www.cs.toronto.edu/~norouzi/research/mih/ Fast Exact Search in Hamming Space with Multi-Index Hashing.
3. https://github.com/kevinlin311tw/caffe-cvprw15 Deep Learning of Binary Hash Codes.
4. http://www.cs.huji.ac.il/~yweiss/SpectralHashing/ Spectral Hashing.

Datases:

1. http://groups.csail.mit.edu/vision/TinyImages/
2. http://www.cs.toronto.edu/~kriz/cifar.html
3. http://www.vision.caltech.edu/Image_Datasets/Caltech101/


~~~
Efficient hamming distance computation:
HammingDistance(x,y) = HammingWeight(x^y)
https://en.wikipedia.org/wiki/Hamming_weight#Efficient_implementation
http://notabs.org/blcutil/
http://stackoverflow.com/questions/12380478/bits-counting-algorithm-brian-kernighan-in-an-integer-time-complexity
https://web.archive.org/web/20100604050922/http://infolab.stanford.edu/~manku/bitcount/bitcount.c
http://graphics.stanford.edu/~seander/bithacks.html#CountBitsSetKernighan

TODO:

1. Semantic hashing.
    https://github.com/gynnash/AutoEncoder
    http://www.cs.toronto.edu/~hinton/MatlabForSciencePaper.html 
    http://www.cs.toronto.edu/~fritz/absps/sh.pdf
2. Locality sensitive hashing with hamming distance.
    http://stackoverflow.com/questions/12952729/how-to-understand-locality-sensitive-hashing
    


Cosine distance:
Approaches different from hamming distance - "Randomly project points to low dimensional bit signatures such that cosine distance is approximately preserved". 
~~~

# Dancing-around-hamming-distance

Collection of various code snippets using hamming distance.

1. http://www.cs.toronto.edu/~norouzi/research/mlh/ Minimal Loss Hashing for Compact Binary Codes.
2. http://www.cs.toronto.edu/~norouzi/research/mih/ Fast Exact Search in Hamming Space with Multi-Index Hashing.
3. https://github.com/kevinlin311tw/caffe-cvprw15 Deep Learning of Binary Hash Codes.
4. http://www.cs.huji.ac.il/~yweiss/SpectralHashing/ Spectral Hashing.

Efficient hamming distance computation:
HammingDistance(x,y) = HammingWeight(x^y)
https://en.wikipedia.org/wiki/Hamming_weight#Efficient_implementation
http://notabs.org/blcutil/

TODO:

1. Semantic hashing.
    https://github.com/gynnash/AutoEncoder
    http://www.cs.toronto.edu/~hinton/MatlabForSciencePaper.html 
2. Locality sensitive hashing with hamming distance.
    http://stackoverflow.com/questions/12952729/how-to-understand-locality-sensitive-hashing
    


Cosine distance:
Approaches different from hamming distance - "Randomly project points to low dimensional bit signatures such that cosine distance is approximately preserved". 

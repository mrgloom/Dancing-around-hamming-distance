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
tags: hamming distance, hamming embedding, binary codes, locality sensitive hashing, semantic hashing, min-hash.

Efficient hamming distance computation:
HammingDistance(x,y) = HammingWeight(x^y)
https://en.wikipedia.org/wiki/Hamming_weight#Efficient_implementation
http://notabs.org/blcutil/
http://stackoverflow.com/questions/12380478/bits-counting-algorithm-brian-kernighan-in-an-integer-time-complexity
https://web.archive.org/web/20100604050922/http://infolab.stanford.edu/~manku/bitcount/bitcount.c
http://graphics.stanford.edu/~seander/bithacks.html#CountBitsSetKernighan
https://github.com/mariusmuja/flann/search?utf8=%E2%9C%93&q=hamming
https://github.com/mariusmuja/flann/blob/6f1d8f808f2605488c2882ce8fcfa3d5569576bc/doc/references.bib

TODO:

1. Semantic hashing.
    https://github.com/gynnash/AutoEncoder
    http://www.cs.toronto.edu/~hinton/MatlabForSciencePaper.html 
    http://www.cs.toronto.edu/~fritz/absps/sh.pdf
2. Locality sensitive hashing with hamming distance.
    http://stackoverflow.com/questions/12952729/how-to-understand-locality-sensitive-hashing
    
Binary features (BRIEF, ORB, BRISK):
http://www.cs.ubc.ca/~lowe/papers/12mujaCRV.pdf 
http://infoscience.epfl.ch/record/126376/files/OzuysalFL07.pdf

http://frahm.web.unc.edu/files/2014/01/Fast-Organization-of-Large-Photo-Collections.pdf

Presentations:
too complicated math, some relations to spectral hashing.
https://www.robots.ox.ac.uk/~vgg/rg/slides/binarycodes.pdf

Cosine distance:
Approaches different from hamming distance - "Randomly project points to low dimensional bit signatures such that cosine distance is approximately preserved". 
~~~

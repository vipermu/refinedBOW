# refinedBOW
First version of the implementation of the Direct Semantic Analysis method (paper avaiable in https://pdfs.semanticscholar.org/e0ca/e64816a9525eaeeeb5be6dfd1e74d1a1ba91.pdf)
in python with the goal of making an algorithm cappable of combining both visual and textual Bag Of Words (BOW) models in one.

Information about Bag of Words models:
- Visual BOW: http://vision.stanford.edu/teaching/cs131_fall1718/files/14_notes.pdf
- Textual BOW: https://en.wikipedia.org/wiki/Bag-of-words_model

In my implementation the Visual and Textual BOW are represented as two different matrices where each row represents the frequency vector of each model.

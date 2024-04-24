Word2vec is a technique in natural language processing (NLP) for obtaining vector representations of words. These vectors capture information about the meaning of the word based on the surrounding words. The word2vec algorithm estimates these representations by modeling text in a large corpus.
Imports:
import os 
import gensim
from nltk import sent_tokenize
from gensim.utils import simple_preprocess
Here in this project we convert an entire corpus of data into vector representation and plot their vector representation.

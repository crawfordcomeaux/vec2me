# vec2me
Experiments in identifying someone's interests/knowledge using word embedding &amp; topic modeling

### Ideas



#### Training data?
- Hacker News headlines (and comments?) ([All HN headlines w/10+ comments from users who've made 10+ comments](https://zenodo.org/record/45901))
- scraped extracted URLs
- use [sense2vec](https://github.com/spacy-io/sense2vec)
- Wikipedia
 


### Research

#### [lda2vec](https://github.com/cemoody/lda2vec) - mixes lda and word2vec
lda2vec paper: [Mixing Dirichlet Topic Models and Word Embeddings to Make lda2vec](https://arxiv.org/pdf/1605.02019v1.pdf)

#### [entity2vec](https://github.com/ot/entity2vec) - finding related info sources (to expand training data?)
entity2vec paper: [Fast and Space-efficient Entity Linking in Queries](www.di.unipi.it/~ottavian/files/wsdm15_fel.pdf))

#### [topicvec](https://github.com/askerlee/topicvec) - a different way of mixing lda w/word vectors
topicvec paper: [Generative Topic Embedding: a Continuous Representation of Documents](https://arxiv.org/pdf/1606.02979v2))

#### [Word Mover's Distance](https://github.com/mkusner/wmd) - proposed future work at end of topicvec paper (unsure if it can be used here)
wmd paper: [From Word Embeddings To Document Distances](http://jmlr.org/proceedings/papers/v37/kusnerb15.pdf) 

#### [tweet2vec](https://github.com/bdhingra/tweet2vec) - predicts hashtags via character-level vectors? (probably not useful for this)
tweet2vec paper: [Tweet2Vec: Character-Based Distributed Representations for Social Media](https://arxiv.org/abs/1605.03481)

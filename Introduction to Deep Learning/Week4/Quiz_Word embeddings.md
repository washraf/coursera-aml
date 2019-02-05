## Question 1: Which of the following is true about word2vec model?
* **It requires human-defined semantic relations between words.**
* It's outputs (predictions) are linear functions of inputs.
* It uses convolutional layers and pooling.
* **It has one trainable parameter per word**.
* **It requires some text corpora for training.**

## Question 2: How can you train word2vec model?
* **By learning to predict omitted word by it's context.**
* By minimizing crossentropy (aka maximizing likelihood).
* By changing order of words in the corpora.
* **By learning to predict context (neighboring words) given one word.**
* By minimizing distance between human-defined synonyms and maximizing distance between antonyms.
* By applying stochastic gradient descent.

## Question 3:Here's an online demo of word2vec model. Let's use it to find synonyms for rare words. Don't forget to choose English GoogleNews model. Which of the following words is in top 10 synonyms for "weltschmerz".
* worldbuilding
* **despair**
* decrystalization
* big_bang

## Question 4: Which of the following is an appropriate way to measure similarity between word vectors v1 and v2? (more = better)
* **-||v1 - v2||**
* ||v1 - v2||
* **cos(v1,v2)**
* sin(v1,v2)

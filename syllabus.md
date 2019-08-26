## Natural language processing in cognitive science

#### Course description
Language data is everywhere, from chatting with friends to writing answers to exam questions. Many cognitive science questions, such as how we represent concepts (Murphy, 1993)  or how we remember the stories people tell us (Loftus & Palmer, 1974)  are tightly coupled with language. Natural language processing (NLP) has the ability to revolutionize how we design and analyze cognitive experiments in the lab, from selecting stimuli for memory tests, to parsing participants’ written responses to a memory prompt or in a diary entry. In this course, we will see how NLP and text analytics can be applied to study cognitive science questions. We will use hands-on case studies from across subdisciplines to illustrate new computational techniques. 

#### Prerequisites
- Introduction to cognitive psychology, linguistics, human factors, or cognitive science
- Basic (beginner) fluency with Python and R
- Willingness to learn and modify code

#### Course objectives
By the end of this course, you will be comfortable with the basic tools of the trade and be confident in your ability to build on your existing skills. You will be able to take a text-based data set and apply it to questions in cognitive science. You will also be more familiar with the most common computational methods used in working with text data and will be able to discuss the pros and cons of different methods.

#### Course topics:

1.	What is NLP?
2.	How is NLP relevant to cognitive psychology?
  *  Design and analysis of experiments
  *  Psycholinguistics
		*  Quantifying linguistic structure
		*  Individual differences (domain knowledge/genre differences/language experience)
	*  Episodic memory
	*  Concepts and categories
3.	What kinds of tools are useful for doing NLP? (What are your needs/use cases?)
	* Virtual environments (virtualenv, [anaconda](mailto:https://medium.com/dunder-data/anaconda-is-bloated-set-up-a-lean-robust-data-science-environment-with-miniconda-and-conda-forge-b48e1ac11646))
	* git/github ([10.1080/00031305.2017.1399928](https://dx.doi.org/10.1080/00031305.2017.1399928]))
	* JupyterHub (technical details here: [link](mailto:https://jupyterhub.readthedocs.io/en/stable/)))
	* Software
		* spaCy, stanfordnlp, gensim, nltk, allennlp, etc.
		* numpy, scipy, pandas, sklearn
	* Other languages? (R, Java, C++)
4.	Text pre-processing
	* Stop words
	  * How to identify and define stop words
	  * Pros and cons of removing them
	* Lemmatization
		* Defining lemmas
		* Typological factors
	* Tokenization
	* Text normalization
		* Rare words and <UNK>
		* Error correction
	* Zipf’s law
	* Languages other than English
5.	Extracting linguistic regularities
	* Selection of corpora, comparable corpora, hapax legomena
	* Lexical co-occurrences
		* Co-occurrences
		* Transition probabilities
		* Mutual information
		* Contextual diversity
	* Long-distance dependencies
	* Grammatical regularities
	* Case studies
		* Impacts of contextual diversity on memory
		* Linguistic ordering preferences across domains
6.	Learning word meanings
	* Latent semantic analysis
	* GloVe
	* word2vec
	* Case studies
		* Semantic priming in lexical decision
		* Predicting word recall
7.	Using text data to predict performance on cognitive tasks
	* What is a “document”?
	* Generalized linear models (lasso and ridge regression)
	* Document representations
		* Bag-of-words representations
		* PCA or LSA on bag-of-words
	* Word embeddings
		* Word-word similarity metrics
		* Using word vectors directly
	* Recurrent neural networks, sentence encoders
	* Case studies
		* Categorizing written or transcribed participant responses
		* Predicting self-paced reading

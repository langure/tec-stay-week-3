# Week 3: Language modeling and N-grams

Language Modeling and N-grams are two fundamental concepts in the fields of Machine Learning (ML) and Natural Language Processing (NLP).

# Language Modeling
Language modeling is a core task in NLP that involves predicting the next word in a sequence based on the words that have already been observed.

A simple example of a language model is one that uses the probability of word occurrence. For example, given the sentence "It is a nice day", the model could predict the next word by calculating the probability of all words in its vocabulary following this sequence.

Modern language models, such as Transformer models like GPT (Generative Pretrained Transformer) and BERT (Bidirectional Encoder Representations from Transformers), go a step further. Instead of simply calculating word occurrence probabilities, these models understand the context of a sentence by learning the underlying structure of the language.

For instance, the GPT model, when given a prompt like "The weather is nice, I think I will go for a ", might suggest "walk", "run", or "drive", because it has learned from numerous text examples that these words often complete this type of sentence.

# N-grams
N-grams are another fundamental tool in NLP, used to represent text or speech as a collection of n-length word sequences.

For instance, the sentence "I like to play football" can be broken into the following 2-grams (bigrams): ["I like", "like to", "to play", "play football"]. And, into 3-grams (trigrams) as follows: ["I like to", "like to play", "to play football"].

These N-grams can be used as features in many NLP tasks. For example, in sentiment analysis, if the phrase "not good" appears frequently in negative reviews, the model can learn to associate this bigram with a negative sentiment.

By analyzing N-grams, ML models can make more informed decisions about what word or phrase comes next. This enables them to perform tasks like text generation, text classification, and many others.

In conclusion, Language Modeling and N-grams are core techniques in NLP. They enable machines to understand and generate human-like text, powering many applications we use daily, from web search to virtual assistants.

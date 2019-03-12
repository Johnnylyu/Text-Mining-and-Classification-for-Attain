# Workforce Analytics with Machine Learning-for-Attain
These are the projects for GWU Practicum with Attain,LLC.
Based on the given resume data,some topic modelling and text classification works are presented here.

The resume mining project mainly focused on the topic of how to select the right person for different plans through machine learning algorithms. There are two parts in this process. The first one is finding the skillsets from Attain employees’ resumes with LDA model. The second one is a classification model utilized to find out the most advisable personnel to the specific job type.

Part 1: The input here is the individual resumes provided from Attain. There are 103 people’s resumes in total and what the LDA model did is classify text in each resume to a particular topic with regarding to word frequency estimators like TF-IDF or Bag of Words. Based on the coherence score which is an estimator used to measure the pairwise word-similarity scores of the words in the topics, the words in those resume text could be concluded in 8 topics which could be the descriptions of specific skillsets in the workforce.

Part 2: With the categories of workforce being discovered in the first part. The next thing we did is implementing a classification model to the given resumes to select the right person for the job. We split the resumes from the Attain to three categories with regarding to their most recent job experience: Project Management, Business Intelligence and Software Development. The model was then trained to recognize resumes with an output of numerical indexes that could be compared to identify the most suitable resume and corresponding person for the job type we need.

![](https://github.com/Johnnylyu/Text-Mining-and-Classification-for-Attain/blob/master/Resume%20Classification.png)

### References

Bird, S. (2016). Natural language processing with python. Place of publication not identified: OReilly Media.

Britz, Denny. “Understanding Convolutional Neural Networks for NLP.” WildML, 10 Jan. 2016, Retrieved from www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/.

Chollet, Francois. “The Keras Blog.” The Keras Blog ATOM, 2016, Retrieved from blog.keras.io/using-pre-trained-word-embeddings-in-a-keras-model.html.

Conneau, Alexis, Schwenk, Holger, Barrault, Lecun, & Yann. (2017, January 27). Very Deep Convolutional Networks for Text Classification. Retrieved from https://arxiv.org/abs/1606.01781

Ignatow, G., & Mihalcea, R. (2017). Text mining: A guidebook for the social sciences. Los Angeles: SAGE

Kim, & Yoon. (2014, September 03). Convolutional Neural Networks for Sentence Classification. Retrieved from https://arxiv.org/abs/1408.5882

Prabhakaran, S. (2018, March). Topic Modeling with Gensim Retrieved from https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/

Susan, Li. (2018, May 31). Topic Modeling and Latent Dirichlet Allocation (LDA) in Python Retrieved from https://towardsdatascience.com/topic-modeling-and-latent-dirichlet-allocation-in-python-9bf156893c24

Zhang, Ye, Wallace, & Byron. (2016, April 06). A Sensitivity Analysis of (and Practitioners' Guide to) Convolutional Neural Networks for Sentence Classification. Retrieved from https://arxiv.org/abs/1510.03820

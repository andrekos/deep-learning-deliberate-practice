# Timeline

* **[Week of 2/18]: Warm-up** 
	* Surveyed materials, warm-up (fast.ai, CS 231N)
	* Created Github [Learning Project](https://github.com/robert8138/deep-learning-deliberate-practice)

* **[Week of 2/25]: Mathematical Formulation of Neural Nets**
	* Warm-up continued
	* Coursera DL course 1 (Basic of NN)
	* Studied backward propogation ([here](http://neuralnetworksanddeeplearning.com/chap2.html), [here](http://colah.github.io/posts/2015-08-Backprop/), and [here](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b)).

* **[Week of 3/4]: Convolutional Neural Network**
	* Keras Book Chapter 1,2,4, and 5 (CNN) 
	* Finished Coursera DL course 2 (Optimization/Hyperparameter Tuning)
	* Study CNN in details (Stanford CS 231N [CovNet Notes](http://cs231n.github.io/convolutional-networks/) being the most useful)

* **[Week of 3/11]: Convolutional Neural Network (Interleaving)**
	* CS 231 coverage on Neural Network formulation
	* Finished Coursera DL course 4 (CNN)

* **[Week of 3/18]: Additional Topics in CNN / Hands-on Coding**
	* CS 231N (CNN Architecture, Visualizing CNN)
	* Deep Learning Software, Running Keras code on Redspot
	* Finished Coursera DL course 3 and started meta-topics on structuring ML projects

* **[Week of 3/25]: Hands-on Coding / Practical Advice for ML/DL**
	* Keras Book Chapter 7 on Functional API
	* Practical Tips for ML projects from Ian Goodfellow
	* Started and completed investigation about Image pipelines & CNN at Airbnb
	* Discovered Stanford CS 230
	* Finally read through [Rules of ML: Best Practice for ML Engineering](https://developers.google.com/machine-learning/rules-of-ml/)

* **[Week of 4/1]: Recurrent Neural Network & NLP**: I am a little bit hesitant to dig too deep in NLP just yet. It's a completely different topic and I still feel I haven't fully grasp CNN, so I will treat this as a quick survey for now. I think the proper way to learn it is to take [CS 224N](http://web.stanford.edu/class/cs224n/index.html).
	* Stanford CS 231N revisit Lecture 10 on RNN
	* Keras Book Chapter 6 on Recurrent Neural Network & RNN using Keras
	* Started Coursera DL course 5 - RNN
	* [CS 244N Word2Vec lecture notes](http://web.stanford.edu/class/cs224n/lectures/lecture2.pdf)

* **[Week of 4/8]: Recurrent Neural Network & NLP (Interleaving)**: to reinforce all the basic things I learned about word embeddings, RNNs from Coursera DL in Stanford class setting again
	* Stanford CS 224N Lecture 2: Word2Vec -> word embeddings
	* Stanford CS 224N Lecture 3: Co-ocurrence, GloVec word embeddings, BLEU scores
	* Stanford CS 224N Lecture 8: Vanilla RNN, Bidirectional RNN, Deep RNN
	* Stanford CS 224N Lecture 9: Gated Recurrent Units (GRU), Long-Short Term Memory (LSTM)
	* [Edwin Chen's explanation on LSTM with visualization](http://blog.echen.me/2014/05/30/exploring-lstms/)
	* [The Unreasonable Effectiveness of Recurrent Neural Network](http://karpathy.github.io/2015/05/21/rnn-effectiveness/): char RNN model -> {Paul Graham essays, Shakespeare, LaTex, C, Linux}

* **[Week of 4/15]: Tensorflow**
	* Stanford CS 224N: Lecture 4 (Backprop I), 5 (Backprop II), 13 (CNN) Review
	* Stanford CS 224N: Lecture 7 on Tensorflow
	* [Stanford CS 20](http://web.stanford.edu/class/cs20si/syllabus.html): Lecture 1-5, a more detailed introduction to Tensorflow
	* Glanced through Tensorflow's [Getting Started Guide](https://www.tensorflow.org/get_started/)
	* Scribed RNN notes in /concepts directory

* **[Week of 4/23]: Unsupervised Learning, Generative Models, Autoencoders**
	* Stanford CS 231 Lecture 13: Generative Model
	* Stanford CS 231 Lecture 16: Adversarial Examples and Adversarial Training
	* Keras Book Chapter 8: Generative Deep Learning
	* Keras Book Chapter 9: Conclusions (finished the book!)
	* [Generate Model from OpenAI](https://blog.openai.com/generative-models/)
	* Scribed CNN & CNN Architecture notes in /concepts directory

* **[Week of 4/30]: Review Week 1, summarize ideas in [/concepts directory](https://github.com/robert8138/deep-learning-deliberate-practice/tree/master/concepts)**
	* Stanford CS 229 Notes on DL, backprop (not as useful)
	* Scribe `learning_algorithms.md`, `learning_tricks.md`, and `learning_enhancement.md` 

* **[Week of 5/7]: Review Week 2, summarize ideas in [/concepts directory](https://github.com/robert8138/deep-learning-deliberate-practice/tree/master/concepts)**
	* Finished reading [Matrix Calculus for Deep Learning](http://parrt.cs.usfca.edu/doc/matrix-calculus/index.html), reminds me a lot of Math 105 - Multivariate Calculus & Measure Theory
	* Went through Michael Nielsen's [detailed treatment on backprop](http://neuralnetworksanddeeplearning.com/chap2.html) again, derived 4 fundamental equations of backprop along the way
	* My ugly derivation is written down [here](https://github.com/robert8138/deep-learning-deliberate-practice/blob/master/concepts/pictures/backprop_math_by_hand.png). This refreshes my Matrix Calculus quite a bit
	* Went through [Why are deep neural networks hard to train?](http://neuralnetworksanddeeplearning.com/chap5.html) and [Yes, you should understand backprop](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b) again, with the backprop derivatives in context
	* Scribed notes for [Neural Network Formulation](https://github.com/robert8138/deep-learning-deliberate-practice/blob/master/concepts/neural_network_architecture_basics.md) - basic structure, terminology, loss function
	* Scribed notes for [Backprop](https://github.com/robert8138/deep-learning-deliberate-practice/blob/master/concepts/backward_propogation.md) - Revisit Gradient calculation for DL

* **[Week of 5/14]: Google CapitalG's Machine Learning Training**
	* [Google CapitalG Machine Learning Training](https://www.cnbc.com/2018/05/19/alphabet-capitalg-machine-learning-bootcamp-for-portfolio-companies.html)
	* [Facebook Machine Open House](https://fb-mlopenhouse.splashthat.com/?gz=c5581790016cf0e56230f7584d387938&pp=1&guest-access-hash=Mjk5OTEyNnwxNjg3NzgyNjZ8MTUyNjQyMzY0MDtlMGQ4MGU4YzA0ZTY1ZTAwMzg1NGRmOTkwODA5YWE4ZTI2OTU0NWJmZWQ5Mjk4NTEwMjU2ZDRiY2E5ZDg2MDEw)
	* [Facebook's Field Guide to Machine Learning](https://research.fb.com/the-facebook-field-guide-to-machine-learning-video-series/)

* **[Week of 5/21]: Review Week 3, summarize word embeddings, Recommender System in [/concepts directory](https://github.com/robert8138/deep-learning-deliberate-practice/tree/master/concepts)**
	* Scribe `word_embeddings.md`
	* Scribe `recommender_system.md`, read [YouTube Recommendation System](https://www.researchgate.net/profile/Sujoy_Gupta2/publication/221140967_The_YouTube_video_recommendation_system/links/53e834410cf21cc29fdc35d2/The-YouTube-video-recommendation-system.pdf) and [YouTube Recommender System with Deep Learning](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45530.pdf)

* **[Week of 5/28]: Scribe deep_learning_history.md & deep_learning_workflow.md**
	* Scribed `deep_learning_history.md`
	* Scribed `deep_learning_workflow.md`
	* Started Scribing `structure_ml_projects.md` (scribed up until Chapter 1-32 from Andrew Ng's ML Yearning book)

* **[Week of 6/4]: Break**

* **[Week of 6/11]: Apply DL on the Job**
	* Set up an simple end-to-end transfer learning pipeline for predicting photo quality issues using Keras ResNet50 model and Airbnb's thumbnail data
	* Finished draft for A Beginner's Guide to Data Engineering - The Series Finale

* **[Week of 6/18, 6/25, 7/2] Break: Wedding in TW**

* **[Week of 7/9, 7/16] Break: 2018 H1 Reflection**

* **[Week of 7/23]: Andrew Ng's Machine Learning Yearning Book**
	* Continue to [scribe notes](https://github.com/robert8138/deep-learning-deliberate-practice/blob/master/concepts/structure_ml_project.md) from Andrew's Machine Learning Yearning

* **[Week of 8/6]: Learn About NIMA**
	* Read [NIMA Paper](https://arxiv.org/pdf/1709.05424.pdf) and learn [AVA dataset](http://refbase.cvc.uab.es/files/MMP2012a.pdf)

* **[Week of 8/13]: Set up DL-hands-on mini project**
	* Setting up AVA dataset [upload](https://github.com/robert8138/deep-learning-deliberate-practice/blob/master/codes/nima/photo_scoring_nima_upload_ava_dataset.ipynb) to data warehouse via AWS/Airflow
	* Setting up [NIMA Retraining Pipeline](https://github.com/robert8138/deep-learning-deliberate-practice/blob/master/codes/nima/photo_scoring_nima_retraining_pipeline.ipynb)

# Upcoming

* **[Week of ?]**: Hands on Exercise
	* Start Applying What I learned on a concrete work related project


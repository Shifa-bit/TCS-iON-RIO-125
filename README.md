# Project Title
Automate Emotion Analysis of Textual Comments and Feedback.
# Project Description:
**Project Objective & Brief:** To develop a deep learning algorithms with an aim to detect different types of emotion contained in a collection of English sentences or a large paragraph and accurately predict the overall emotion of the paragraph.

**Project Guidelines:** 
1. Identitfy and finalize a collection of English text, sentence or large paragraphs covering emotions like happy, sad, expressing love, anger or surprise.
2. Develop a deep learning model for detection & segmentation of emotions contained in the text, sentence or paragraph.
3. The above model should also accurately handle scenarios where the following are present:
a. Sarcastic meaning
b. Double negation words
c. Abbreviations like ('nxt', '2mrw', 'things r gd', etc).
4. Enhance the previous algorithm to accurately predict the overall emotion of the text, sentence or paragraph.
5. Test the model for accuracy.

**Expected Project Outcome:** 
1. Algorithm to detect different types of emotion from a paragraph. 
2. Algorithm to predict overall emotion of the paragraph. 
3. Detailed presentation with proof of reasonable accuracy.

**Hands-on Environment or Software Requirements to Implement the Project:**
1. Google Collab (https://collab.research.google.com) 
2. Python, Java (opt.), Eclipse, Ubuntu OS (opt.) / VirtualBox 

In Emotion analysis, the data mainly focuses on whether the feedback to a product is :

- negative
- positive
- neutral

This provides a top level review of the product and its acceptance in the market.

- Emotion Analysis provides a deeper insight of consumer emotions.
- Analyzing textual feedback to the level of reading between lines.
- Categorizing feedback and analyzing its emotion by picking up words, contexts, patterns, behaviors. This can be even taken to the level of individual’s expressive capability of a particular situation.

# Approaches to Text Classification
- **Rule Based Systems:**
1. Rule-based approaches classify text into organized groups by using a set of linguistic rules.
2. Each rule comprises of a pattern based on semantics and its predicted category. 
- **Machine Learning based Systems:**
1. Text classification based on past observations.
2. By using training data, the algorithm can learn the different associations between pieces of text and that a particular output (i.e. tags) is expected for a particular input (i.e. text).
3. Feature extraction: Transforms each text into a numerical representation in the form of a vector. E.g. bag of words [a vector represents the frequency in a predefined dictionary of words ]
4. The algorithm is fed with training data consisting of feature sets.
5. Once trained with enough training samples, the machine learning model can begin to make accurate predictions on unseen text with similar feature sets.

# Text Classification Algorithms
Some of the most popular machine learning algorithms for creating text classification models include the naive bayes family of algorithms, support vector machines, Regressions, and deep learning algorithms with CNN and RNN. Metrics and Evaluation Cross-validation is a common method to evaluate the performance of a text classifier.

1. It consists in splitting the training dataset randomly into equal-length sets.
2. For each set, a text classifier is trained with the remaining samples (e.g. 75% of the samples).
3. The classifiers make predictions on their respective sets and the results are compared against the human-annotated tags.
4. With these results, a performance metrics is built, that are useful for a quick assessment on how well a classifier works.

**Performance metrics normally includes:**
- **Accuracy:** the percentage of texts that were predicted with the correct tag.
- **Precision:** the percentage of examples the classifier got right out of the total number of examples that it predicted for a given tag.
- **Recall:** the percentage of examples the classifier predicted for a given tag out of the total number of examples it should have predicted for that given tag.
- **F1 Score:** the harmonic mean of precision and recall.

# Data Sources to solve problem
- Data Sets from any open source data sources can be used. Model building and solution engineering is NOT restricted to data.
- Example:
 1. https://ai.stanford.edu/~amaas/data/sentiment/
 2. https://data.world/crowdflower/sentiment-analysis-in-text
 3. https://www.kaggle.com/crowdflower/twitter-airline-sentiment













    

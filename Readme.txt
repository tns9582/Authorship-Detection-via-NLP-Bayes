Project Overview
This project analyzes textual data to predict the most likely author of an essay using linguistic features. Using the Federalist Papers, authored by Alexander Hamilton, James Madison, and John Jay, we apply a combination of exploratory data analysis (EDA), feature extraction, and machine learning classification models to resolve the authorship of disputed essays.

Key data science methods used:

Text preprocessing (tokenization, stopword removal, normalization)
Feature engineering using word frequencies and function word analysis
Naive Bayes classification to build author profiles
Model evaluation using accuracy and confusion matrices

Methodology
📂 Data Sources
Essays grouped by authors: Hamilton, Madison, Jay, and Disputed
Stopwords file for filtering common language terms

🧹 Preprocessing
Lowercasing text
Extracting words using regex
Removing stopwords
Stemming with the Lancaster stemmer

📊 Modeling
Calculated prior probabilities based on undisputed essays
Computed word likelihood for each author
Built a descriptive model using Bayes Rule
Predicted authorship of disputed essays using highest posterior probability

Key Results
Most frequent words differed among authors, helping distinguish writing style
Posterior probabilities successfully identified most likely authors for disputed essays
Word frequency bar charts helped visualize stylistic differences

Visualizations
Bar charts showing word usage differences among Hamilton, Madison, and Jay, highlighting the most influential words per author.

Conclusion
This project showcases the power of textual data processing for solving authorship attribution problems. By modeling word frequencies and applying a simple probabilistic approach, I replicated historical insights and gained hands-on experience with natural language processing techniques.

# imdb_sentiment_analysis
### Contents
This repository contains two Jupyter notebooks that outline my approach for the Kaggle Bag of Words Meets Bags of Popcorn contest. Enclosed in the first notebook are methods that produce features from the labeled data provided. The second notebook takes said features and creates a model which predicts outcomes from the unlabeled data also provided.

### Description of CSV Files
1. Download competition data from the following link and place csv files into datasets repository: https://www.kaggle.com/c/word2vec-nlp-tutorial/data 
2. Run the 1_imdb_eda_fg.ipynb notebook to create the features csv "merged_desc_12g.csv," which is also placed in the datasets repository upon running.
3. Run the 2_imdb_model.ipynb notebook to create the predictions csv "log_reg_bag.csv," which will be placed in the submissions repository upon running.

### Libraries
1. For Data Cleanup and Feature Generation: numpy, pandas, sklearn, scipy, regex, ntlk, BeautifulSoup
2. For Predictive Modeling: sklearn, xgboost
3. For Visualizations: matplotlib, seaborn

### Run Time/Hardware
Runs in about 15 minutes on a fairly high-powered desktop (i7-4790) with 16 gb of RAM. May clog up the ram on smaller machines.





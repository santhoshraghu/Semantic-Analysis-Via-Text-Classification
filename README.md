# Semantic-Analysis-Via-Text-Classification
Semantic Analysis Via Text Classification on the official Amazon Fine Food Reviews Dataset   - https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews


In this assignment, the goal was to re-investigate text classification problems using more sophisticated content embedding techniques such as word2vec and BERT models. The task involved implementing a review sentiment classification task via Amazon Fine Food Reviews dataset.

### Dataset:
The dataset comprised reviews of fine foods from Amazon spanning over a period of more than 10 years, including all ~500,000 reviews up to October 2012. The reviews included product and user information, ratings, and plain text reviews.

### Overview:
1. Installed/Imported necessary packages.
2. Conducted Exploratory Data Analysis (EDA).
3. Created labels based on the score: score > 3 labeled as positive, score < 3 labeled as negative.
4. Resampled for imbalanced datasets if necessary.
5. Used 10-20% of the sub-dataset and split it into training and test sets.
6. Used text and created labels as features and ground truth for completing the following tasks.

### Overview:

#### TFIDF approach:
Implemented TFIDF-based classification using the methods proposed in assignment 1.

#### Review classification using word2vec:
Implemented word2vec-based classification using the methods proposed in assignment 1.

#### BERT (without fine-tune):
Used the pretrained BERT pipeline ('sentiment-analysis') for review classification without fine-tuning.

#### BERT (with fine-tune):
Fine-tuned the BERT model for review classification using the deliverables from the BERT Model.

####  BERT (with LoRA):
Defined the LoRA configuration and fine-tuned the BERT model using LoRA for review classification.

#### Results Analysis:
Summarized all results in a table and interpreted the results, including why one method might outperform another.

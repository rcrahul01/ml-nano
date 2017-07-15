# Capstone project
Capstone for Udacity's Machine Learning Nanodegree

## Finding pairs of duplicate questions
Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both groups in the long term. Ideally, these duplicate questions would be merged together into a single canonical question, as doing so would provide several benefits: 
• It saves the question asker time if their question has already been answered previously on the site. 
 • Frequently repeated questions can frustrate highly engaged users whose feeds become polluted with redundant questions. 
• Q&A knowledge bases have more value to users and researchers when there is a single canonical question and collections of answers, 
• Having knowledge of alternative phrasings of the same question can improve search and discovery. 

A prevalent problem in online Q&A forums like Stack Overflow, Stack Exchange and Quora, for which combining the answers for duplicate questions asked by their users improves the efficiency and the quality of their service.
Relevant work: https://web.stanford.edu/class/cs224n/reports/2748045.pdf
I will perform numerous experiments using publicly available Quora’s Question Pairs dataset https://www.kaggle.com/c/quora-question-pairs/data,  which consists of 400000 pairs of questions labeled as duplicates or not duplicates.

## Datasets
The necessary datasets for this project can be found in the webpage of the Kaggle's project, which is
the following: https://www.kaggle.com/c/quora-question-pairs/data under the names _train.csv.zip_ and 
_test.csv.zip_. Both of them should be put in a folder called _data_

## Code
All the necessary Python code used for this project can be found in the file named capstone_project_code.ipynb.

## Software requirements
The following software is required to be installed in order to run the code:
* Python 3.5 or higher
* Scipy
* Numpy + MKL
* Pandas
* Matplotlib
* Tqdm
* Nltk (Natural Language ToolKit)
* Sklearn
* XGBoost (The instructions for installing this library are found here: 
http://xgboost.readthedocs.io/en/latest/build.html.

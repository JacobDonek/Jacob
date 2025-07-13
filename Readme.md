#Jacob Donek Machine Learning CA 

This project developed a proof-of-concept system that clusters Twitter users based on behavioural features
using unsupervised machine learning. It uses a dataset of tweets from the Israel-Palestine conflict and 
applies KMeans and DBSCAN for clustering.

Additional supporting documents: https://github.com/JacobDonek/MachineLearningCA
_____________________
#Project Dependencies

It is highly recommended to open the project files in Jupyter Notebook (Python 3.9+)
within Anaconda. The following packages are essential and should be included
in Jupyter Notebook:

-pandas
-numpy
-matplotlib
-seaborn
-scikit-learn
-nltk
-tqdm

If any library gives an error, run the following in a new cell: 

!pip install pandas numpy matplotlib seaborn scikit-learn nltk tqdm

___________________
#Installation Steps

1. Download the project files
2. Unzip in a new folder
3. Dataset "Tweets.csv" should load as it is programmed to do so from its folder
   -> If you encounter an error, copy this file into the same directory as "Jacob_Donek_ML_Code.ipynb"
4. Download NRC Emotion Lexicon from https://github.com/aditeyabaral/lok-sabha-election-twitter-analysis/blob/master/NRC-Emotion-Lexicon-Wordlevel-v0.92.txt
   and place into the same directory as "Jacob_Donek_ML_Code.ipynb". 

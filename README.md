# NIPS 2017 competition
Data &amp; Scripts for develop a machine learning algorithm that automatically classifies genetic variations. 

### What is this repository for? ###
* This is for the "Personalized Medicine: Redefining Cancer Treatment" Kaggle competiton. 
* This script is still a work in progress. For example the gradient boosting implementation still needs a lot of troubleshooting. Segmentation and Documentation of the different steps of the Notebook also need to be done. The current runtime also exceeds Kaggle's 20-minute limit on kernel times.
* Version: stable

### How do I get set up? ###

* To set up, clone the repository or download a .zip file with the repository to your desired directory. Make sure that the directory contains a folder titled "data" to include the MNIST and CelebA folders in.
* The Supporting Data files can be found here: [Test Text](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/test_text.zip), [Test Variants](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/test_variants.zip), [Training Text](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/training_text.zip), and [Training Variants](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/training_variants.zip) (These were too large to fit in my Github).
* To start, run the Jupyter Notebook application in an environment (such as that created by Anaconda) with the skikit-learn, numpy, pandas, jupyter notebook, and xgboost packages. xgboost may require special [installation instructions](https://www.ibm.com/developerworks/community/blogs/jfp/entry/Installing_XGBoost_For_Anaconda_on_Windows?lang=en).

### Contribution guidelines ###

* This repository can easily be forked and contributed to on Github. Feel free to send a pull request.

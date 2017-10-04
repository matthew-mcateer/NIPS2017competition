# NIPS 2017 competition
Data &amp; Scripts for develop a machine learning algorithm that automatically classifies genetic variations. 
### Background ###

Ever since the completion of human genome project, many have been projecting the advent of an era where personalized medicine will be able to beat cancer using specific information from our genomes. It sounds simple enough; by knowing precisely the mutations one carries, one could understand right down to the molecular level how the cancer came about, how it works, and how to fight it. 

Unfortunately, there are still two major obstacles to this vision: The genomic diversity of cancer, and the manpower limitations of the current research. 

Cancer arises when mutations occur that disrupt growth inhibition, promote telomerase immortalization, confer angiogenic ability, etc. The problem is that it's not just cancer cells that accumulate mutations. Our bodies' cells to not retain completely unchanged copies of the 3-billion-bp genome throughout our lives, they have countless harmless (or neutral) mutations that do not show up.

The default method for categorizing these methods is very time-inefficient. With few exceptions, most mutation interpreatations are done manually. This requires a researcher to manually identify, review, and classify any and all mutations based on increasingly verbose and SEO-optimized scientific papers. 

Given this massive state space of unique mutations, it makes sense that the manual approach has not yielded this Holy Grail of personalized medicine yet.

Memorial Sloan Kettering Cancer Center (MSKCC) has asked for help to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations. MSKCC is making available an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations.

### What is this repository for? ###
* This is the data and code for responding to the ["Personalized Medicine: Redefining Cancer Treatment" Kaggle competiton](https://www.kaggle.com/c/msk-redefining-cancer-treatment). 
* The following datasets are contained in this repository: Original Dataset with Gene-Mutation-Text Annotation.
* Everything needed to get started running or contributing, other than a few select python packages, should be available in this repository
* Rather than being limited by Kaggle's 20-minute limit on kernel times, the goal of these scripts were to create the optimal F1 score based on additional data sources not used for the competiton.
* This is a stable release

### Project components ###
* Visualization of variation and categorization of text data
* Normalizing text and class data using bootstrapping and NLP techniques
* Develop context-dependent and context-independent text models
* Testing XGboost, Random Forest, Support Vector Machines, and a variety of other ML algorithms
* Using the F1 score to optimize for precision and recall across nine variant classes classes

### How do I get set up? ###

* To set up, clone the repository or download a .zip file with the repository to your desired directory.
* The Supporting Data files can be found here: [Test Text](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/test_text.zip), [Test Variants](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/test_variants.zip), [Training Text](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/training_text.zip), and [Training Variants](https://www.kaggle.com/c/msk-redefining-cancer-treatment/download/training_variants.zip) (These were too large to fit in my Github).
* To start, run the Jupyter Notebook application in an environment (such as that created by Anaconda) with the skikit-learn, numpy, pandas, jupyter notebook, and xgboost packages. xgboost may require special [installation instructions](https://www.ibm.com/developerworks/community/blogs/jfp/entry/Installing_XGBoost_For_Anaconda_on_Windows?lang=en).

### Contribution guidelines ###

* This repository can easily be forked and contributed to on Github. Feel free to work on your own improvements and send a pull request.

### Future Directions ###
**Data:**
* Addition of Genia, Oncogene, and other pubmed papers to data for training
* Incorporation of Spacy, Gensim, & NLTK

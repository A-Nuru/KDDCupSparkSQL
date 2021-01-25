### Installation

This project requires **Python 3.x** and the following Python libraries installed:

- [Jupyter Notebook](https://jupyter.org/install.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Introduction
* The objective of this work is to explore the KDDCup dataset using Spark SQL. That is, read data and understand its features.
* We ask and answer some questions about the dataset using  Spark SQL and DataFrames.
* We also ask and asnswer some questions about the dataset using  Spark RDD.
* We visualise our analysis using Pandas dataframe and Matplotlib libraries

### Data
The dataset used is the KDDCup dataset. KDDCup-99 is the data set used for The Third International Knowledge Discovery and Data Mining Tools Competition, which was held in conjunction with KDD-99, the Fifth International Conference on Knowledge Discovery and Data Mining. The competition task was to build a network intrusion detector, a predictive model capable of distinguishing between ‘bad’ connections, called intrusions or attacks, and ‘good’ normal connections. This database contains a standard set of data to be audited, which includes a wide variety of intrusions simulated in a military network environment. This dataset has 22 types of bad connections, namely; back, buffer_overflow, ftp_write, guess_passwd, imap, ipsweep, land, loadmodule, multihop, neptune, nmap, perl, phf, pod, portsweep, rootkit, satan, smurf, spy, teardrop, warezclient, warezmaster.

- Download the data [here.](http://kdd.ics.uci.edu/databases/kddcup99/kddcup.data.gz)
- The features are described [here.](http://kdd.ics.uci.edu/databases/kddcup99/task.html)
- You can find more description about the dataset [here.](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)


### File Descriptions
* KDDCupSparkSQL.ipynb - Spark SQL notebook
* KDDCupSparkRDD.ipynb - Spark RDD notebook
* readme.md - Readme file
* license.txt - license file

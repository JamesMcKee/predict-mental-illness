# predict-mental-illness

Scripts for exploring the Kaggle Depression Dataset by Anthony Therrien, DOI 10.34740/kaggle/dsv/8993708 and see https://www.kaggle.com/datasets/anthonytherrien/depression-dataset/data

Tested on python 3.10.16

Note: the data set is too big to host on github and should be downloaded separately. Place in the scr/ directory and both scripts will find it.

Install requirements with:
pip install -r requirements.txt

* There are a lot of requirements because it was painful getting gender-guesser to work, ended up just pip freezing the environment that worked. If you can find the exact incantation needed to minimally install the modules, please let me know!

depression_eda.ipynb has an exploratory data analysis of the data set where correlations between variables are explored 

build_mental_health_model.ipynb trains and tests a random forest model to predict whether a person will have a history of mental illness 

Model accuracy is low at 0.67. Do not use this model to inform any real life decisions. 


# Note
* This comes with absolutely no warranty
* Free software under MIT license
* Please contact James McKee for any questions relating to usage

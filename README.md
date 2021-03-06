ds_course_finalprj
==============================
This is Ruixin's final project for t81_577_datascience course at Washington University. 



!!! Important: The most important file is the notebook [sentiment_analysis.ipynb](https://github.com/ruixinhan/ds_course_finalprj/blob/master/notebooks/sentiment_analysis.ipynb). And the datasets I used are [train.csv](https://github.com/ruixinhan/ds_course_finalprj/blob/master/data/train.csv) and [test.csv](https://github.com/ruixinhan/ds_course_finalprj/blob/master/data/test.csv).



The datasets were downloaded from https://www.kaggle.com/c/tweet-sentiment-extraction. They are datasets in an ongoing kaggle competition called Tweet Sentiment Extraction. However, this competition is not like traditional sentiment analysis competitions asking for sentiment scores, it asked us to extract part of the tweet (word or phrase) that reflects the sentiment.

Caution: I didn't use these datasets to do the tasks of what kaggle asked, because I don't think the selected texts in the trainning data set make sense(there are a lot of similar complains among competitors). But I really like the datasets. Therefore, I used these datasets to build supervised sentiment classifiers.

This project is mainly about sentiment analysis. It is the interpretation and classification of emotions (positive, negative and neutral) within text data using text analysis techniques. Sentiment analysis allows businesses to identify customer sentiment toward products, brands or services in online conversations and feedback.

The essence of sentiment analysis is text (multi) classification. In my datasets, both the train and the test are well labled with whether the twitter text is positive, neutral or negative. I built supervised models to classify them from scratch.


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── train.csv      <- The train dataset.
    │   └── test.csv       <- The test dataset.
    │      
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `conda env export > environment. yml`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------
The work I submitted represents my work and my work alone.  I abode by the academic integrity policy and I am aware of the consequences associated with engaging in academic misconduct. 

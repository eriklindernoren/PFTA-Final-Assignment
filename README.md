# Python for Text Analysis - Final Assignment
## About
This is my submission to the final assignment of the course Python for Text Analysis, taken at Vrije Universiteit in Amsterdam. I chose a binary classification task of training a model that discriminates between whether an article is a blog or news article. I compare my solution, in which I have cherry-picked features based on the task, with a model that trains on features automatically extracted by a bag-of-words model provided by Scikit-learn. The dataset from which I extracted these features is described below. In the end it turned out that my model trained on the 26 features I selected performs on par with the bag-of-words model, which extracts over 100 000 features.

## Setup
    pip3 install -r requirements.txt

## Dataset
    http://research.signalmedia.co/newsir16/signal-dataset.html

<i>
  This dataset is released by Signal Media to facilitate conducting research on news articles. It can be used for submissions to the NewsIR'16 workshop, but it is intended to serve the community for research on news retrieval in general.

  The articles of the dataset were originally collected by Moreover Technologies (one of Signal's content providers) from a variety of news sources for a period of 1 month (1-30 September 2015). It contains 1 million articles that are mainly English, but they also include non-English and multi-lingual articles. Sources of these articles include major ones, such as Reuters, in addition to local news sources and blogs.
</i>

## Run  
 * Handcrafted features
    1. Generate feature set with `notebooks/build_feature_set.ipynb`
    2. Visualize with `notebooks/visualize_data.ipynb`
    3. Text classification with `notebooks/text_classification.ipynb` (~76%)
 * Scikit-learn feature extraction
    1. Generate feature set and classify with `notebooks/bag_of_words_model.ipynb` (~76%)

## Setup
    pip3 install -r requirements.txt

## Dataset
    http://research.signalmedia.co/newsir16/signal-dataset.html

<i>
  This dataset is released by Signal Media to facilitate conducting research on news articles. It can be used for submissions to the NewsIR'16 workshop, but it is intended to serve the community for research on news retrieval in general.

  The articles of the dataset were originally collected by Moreover Technologies (one of Signal's content providers) from a variety of news sources for a period of 1 month (1-30 September 2015). It contains 1 million articles that are mainly English, but they also include non-English and multi-lingual articles. Sources of these articles include major ones, such as Reuters, in addition to local news sources and blogs.
</i>

## Run  
* Cherry-picked features
  1. Generate feature set with `notebooks/build_feature_set.ipynb`
  2. Visualize with `notebooks/visualize_data.ipynb`
  3. Text classification with `notebooks/text_classification.ipynb` (~75% test set accuracy)
* Scikit-learn feature extraction
  1. Generate feature set and classify with `notebooks/bag_of_words_model.ipynb` (~75% test set accuracy)

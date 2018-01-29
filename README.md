# Python for Text Analysis - Final Assignment

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
    1. Generate feature set with `build_feature_set.ipynb`
    2. Visualize with `visualize_data.ipynb`
    3. Text classification with `text_classification.ipynb` (75%)
 * Scikit-learn feature extraction
    1. Generate feature set and classify with `bag_of_words_model.ipynb` (76%)

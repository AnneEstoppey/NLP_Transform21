# NLP_Transform21

In this Jupyter Notebook, we will explore different aspects of NLP (Natural Language Processing). We will use well report summaries which are published by the NPD (Norwegian Petroleum Directorate), by requesting via an API. We will go through the different stages of text cleaning and formatting before moving on to NLP processing: tokenization, lemmatization and finally topic modeling.</br>

Please check out notebook here:</br>
```
/notebooks/NLP_transform21_v01_work.ipynb
```
Link to presentation video: https://youtu.be/Sh_zgiptTqw

## In this notebook, we will go through the following steps:
- Get request to NPD wellbore tables via API, we are interested in:
  - wells with coordinates (with-coordinates) and 
  - wells with report summary (with-history)
- Reformating using pandas dataframes - merging of dataframe with coordinates together with dataframe with report summaries
- Visualisation on maps for QC and evaluation of how the data is distributed geographically (North Sea, Norwegian Sea, Barents)
- Cleaning of summaries (removing tags, etc)
- Pre processing for NLP (removing stopwords, tokenisation, lemmatization)
- Exploring wells with WordClouds
- Further NLP analysis: topic modeling and visualisation with pyLDAvis
- Conclusions, what to do next?

## Teasers!
<p align="center">
   <img src="https://user-images.githubusercontent.com/35219455/236476784-2c9b590a-b967-40c1-9ce2-57912d07eadf.jpg" width="750">
   <img src="https://user-images.githubusercontent.com/35219455/236476971-51bbce04-2ac3-4bb0-9539-e731b6aac349.jpg" width="400">
</p>
<b>Topic modeling with pyLDAvis:</b>
<br><p align="left">
   <img src="https://user-images.githubusercontent.com/35219455/236477082-04736200-282a-41ea-8f25-b3ca0f36a478.jpg" width="850">
</p>

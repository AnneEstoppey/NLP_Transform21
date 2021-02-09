# NLP_Transform21
UPDATE: I will post the final version of this notebook right before TRANSFORM 2021 conference, so check it out again mid April!

This is totally UNDER CONSTRUCTION! :-)

In this repo we will work with Wellbore report summaries from Norwegian Petroleum Directorate (NPD). 
The wellbore datasets are public domain and are available here: https://hotell.difi.no/?dataset=npd/wellbore/with-history (well report summaries).</br>
Please check out notebook here:</br>
```
/notebooks/NLP_transform21_v01.ipynb
```
[TRANSFORM 2021 conference](https://softwareunderground.org/transform-2021)

## General description of workflow:
- Get request to NPD wellbore tables via API, we are interested in 1) wells with coordinates (with-coordinates) and 2) wells with report summary (with-history)
- Reformating into pandas dataframes - merging of dataframe with coordinates together with dataframe with report summaries
- Visualisation on maps for QC and evaluation of how the data is distributed geographically (North Sea, Norwegian Sea, Barents)
- Cleaning of summaries (removing tags, etc)
- Pre processing for NLP (removing stopwords, tokenisation, etc)
- Exploring wells with WordClouds
- Further NLP analysis (under construction) with visualisations

## Teasers!
<img src="images/wells_with_report_summary.png" width="750">
<img src="images/wordcloud_well_1_2-1.jpg" width="400">

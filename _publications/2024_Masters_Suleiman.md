---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Content-enriched Popularity Prediction for Music Tracks" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: msthesis
abstract: "The music industry is constantly growing, driven by technological advances that are reshaping how music is produced, distributed, and enjoyed by audiences. Accurately predicting music popularity is becoming a critical ability for artists, producers, and other stakeholders in the music industry.  Previous research has mainly considered the problem of predicting music track popularity as a classification or ranking problem, often simplifying it into binary outcomes such as popular or not popular classes. In this thesis, we take a different perspective and study the prediction of a music track's popularity, and define it as the daily percentage of listening events of a track using time series forecasting models. Additionally, the study aims to enrich these models with various types of content features (visual, audio, textual) derived from the tracks themselves, exploring the impact of these features on the prediction process. Two primary models are employed: DeepAR, a probabilistic Recurrent Neural Network (RNN)-based forecasting model, and Temporal Convolutional Networks (TCN), a variant of Convolutional Neural Networks (CNNs) designed to tackle sequence data. These models are initially trained using historical listening data and subsequently augmented with content features. Furthermore, a baseline Vector Autoregressive Integrated Moving Average (VARIMA) model was also utilized for comparison purposes. Our evaluations show that while employing content features can improve the performance and predictive power of the DeepAR model, these improvements are feature and step-specific, indicating the need for careful feature engineering and selection. In contrast, the TCN model excels in scenarios with longer forecasting horizons but shows mixed results with the integration of content features. However, both models outperformed our baseline VARIMA model."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: 
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True

institution: Johannes Kepler University Linz 
thesis_type: Master's Thesis
advisors : 
- schedl
- moscati


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: master-thesis
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Muhammad Suleiman 

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/obvulihs/content/titleinfo/10275167

# what is the publication type and other bib specific properties
bibentry: misc
bib:
  journal: # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  editor: 
  publisher: 
  address: 
  doi: 	# e.g.10.1109/TVCG.2020.3012063
  url: 
  volume: 
  number: 
  pages: 
  month:
  school: Johannes Kepler University Linz 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code:

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---




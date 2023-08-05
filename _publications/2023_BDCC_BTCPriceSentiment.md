---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Predicting the Price of Bitcoin Using Sentiment-Enriched Time Series Forecasting" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Recently, various methods to predict the future price of financial assets have emerged. One promising approach is to combine the historic price with sentiment scores derived via sentiment analysis techniques. In this article, we focus on predicting the future price of Bitcoin, which is currently the most popular cryptocurrency. More precisely, we propose a hybrid approach, combining time series forecasting and sentiment prediction from microblogs, to predict the intraday price of Bitcoin. Moreover, in addition to standard sentiment analysis methods, we are the first to employ a fine-tuned BERT model for this task. We also introduce a novel weighting scheme in which the weight of the sentiment of each tweet depends on the number of its creator’s followers. For evaluation, we consider periods with strongly varying ranges of Bitcoin prices. This enables us to assess the models w.r.t. robustness and generalization to varied market conditions. Our experiments demonstrate that BERT-based sentiment analysis and the proposed weighting scheme improve upon previous methods. Specifically, our hybrid models that use linear regression as the underlying forecasting algorithm perform best in terms of the mean absolute error (MAE of 2.67) and root mean squared error (RMSE of 3.28). However, more complicated models, particularly long short-term memory networks and temporal convolutional networks, tend to have generalization and overfitting issues, resulting in considerably higher MAE and RMSE scores.
" # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: BTC_Price_Sentiment
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_btc_price_sentiment.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2023_btc_price_sentiment.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- frohmann
- Karner, Manuel
- Khudoyan, Said
- Wagner, Robert
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: MDPI BDCC
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Big Data and Cognitive Computing
  booktitle: 
  editor: 
  publisher: MDPI
  address:
  location: 
  doi: 10.3390/bdcc7030137
  url: https://www.mdpi.com/2504-2289/7/3/137
  volume: 7
  number: 3
  pages: 20
  month: August

preprint:	 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# state key of an internal tool. This will link to the tool site e.g. lineup (usually not needed)
project: 

# Use this if you have an external project website e.g. https://ordino.caleydoapp.org/
external-project: 

# (deprecated)
# # The key of the video .md file (in _videos subfolder)
# video: 
# # The key of the preview video .md file (in _videos subfolder)
# preview-video:

# the youtube-id of the video
youtube-id:
# the youtube-id of the preview-video
preview-youtube-id: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
# pdf: /assets/pdf/ProtoMF__Prototype_based_Matrix_Factorization.pdf
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
# code: https://github.com/hcai-mms/ProtoMF

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

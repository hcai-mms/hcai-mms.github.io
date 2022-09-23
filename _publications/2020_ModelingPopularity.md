---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Modeling Popularity and Temporal Drift of Music Genre Preferences" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "In this paper, we address the problem of modeling and predicting the music genre preferences of users. We introduce a novel user modeling approach, BLLu, which takes into account the popularity of music genres as well as temporal drifts of user listening behavior. To model these two factors, BLLu adopts a psychological model that describes how humans access information in their memory. We evaluate our approach on a standard dataset of Last.fm listening histories, which contains fine-grained music genre information. To investigate performance for different types of users, we assign each user a mainstreaminess value that corresponds to the distance between the user’s music genre preferences and the music genre preferences of the (Last.fm) mainstream. We adopt BLLu to model the listening habits and to predict the music genre preferences of three user groups: listeners of (i) niche, low-mainstream music, (ii) mainstream music, and (iii) medium-mainstream music that lies in-between. Our results show that BLLu provides the highest accuracy for predicting music genre preferences, compared to five baselines: (i) group-based modeling, (ii) user-based collaborative filtering, (iii) item-based collaborative filtering, (iv) frequency-based modeling, and (v) recency-based modeling. Besides, we achieve the most substantial accuracy improvements for the low-mainstream group. We believe that our findings provide valuable insights into the design of music recommender systems." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: http://doi.org/10.5334/tismir.39
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True

#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: ModelingPopularity
# add a 2:1 aspect ratio (e.ghttps://www.frontiersin.org/articles/10.3389/frai.2020.508725., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2020_tismir_modelingpop.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2020_tismir_modelingpop_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Lex, Elisabeth  
- Kowald, Dominik
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: TISMIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2020

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: 

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Transactions of the International Society for Music Information Retrieval # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  editor: 
  publisher: 
  address: 
  doi: 10.5334/tismir.39		# e.g.10.1109/TVCG.2020.3012063
  url: http://doi.org/10.5334/tismir.39
  volume: 3
  number: 1
  pages: "17--30"
  month: 

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






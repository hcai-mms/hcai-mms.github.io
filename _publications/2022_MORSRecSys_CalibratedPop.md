---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Exploring Cross-group Discrepancies in Calibrated Popularity for Accuracy/Fairness Trade-off Optimization" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Popularity bias is an important issue in recommender systems, as it affects end-users, content creators, and content provider platforms alike. It can cause users to miss out on less popular items that would fit their preference, prevent new content creators from finding their audience, and force providers to pay higher royalties for serving expensive popular content. Over the past years, various approaches to mitigate popularity bias in recommender systems have been proposed. Among them, post-processing methods are widely accepted due to their versatility and ease of implementation. While previous studies have investigated the effects of different post-processing techniques on accuracy and fairness of recommendations, the influence of different algorithms on different user groups have not received much attention in this context. Addressing this research gap, we study the effect of a recent mitigation strategy, Calibrated Popularity, in conjunction with a selection of state-of-the-art recommender algorithms including BPR, ItemKNN, LightGCN, MultiVAE, and NeuMF. We show that these algorithms demonstrate different characteristics in terms of the trade-off between accuracy and fairness, both within and between various user groups defined by gender and inclination towards consumption of mainstream items. Finally, we demonstrate how these discrepancies can be exploited to achieve a more effective trade-off between utility and fairness of recommender systems." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://ceur-ws.org/Vol-3268/paper5.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: CaliPopExploring
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
# image_large: 2022_recsyslbr_popbiasgender_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- lesota
- brandl
- Wenzel, Matthias
- melchiorre
- Lex, Elisabeth
- rekab-saz
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CEUR Workshop Proceedings
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2022

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 2nd Workshop on Multi-Objective Recommender Systems co-located with 16th {ACM} Conference on Recommender Systems (RecSys 2022), Seattle, WA, USA, 18th-23rd September 2022
  editor: 
  publisher: CEUR-WS.org
  address: 
  doi:		
  url: https://ceur-ws.org/Vol-3268/paper5.pdf
  volume: 
  number: 
  pages: 
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

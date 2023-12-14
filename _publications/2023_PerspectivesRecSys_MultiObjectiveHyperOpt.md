---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Multiobjective Hyperparameter Optimization of Recommender Systems" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "The quality of recommendations can be evaluated in terms of accuracy and beyond-accuracy metrics; this renders recommendation a multiobjective task. Several works apply multiobjective optimization techniques for training recommender systems (RSs) or for late fusion of recommendations. However, for the hyperparameter selection, only accuracy is considered. In this paper, we  include metrics for accuracy, coverage, novelty, and fairness of recommendations towards groups of users of different activity, and items of different popularity, in the hyperparameter optimization of RSs. We apply the concept of Pareto dominance to select the optimal hyperparameter configurations. Then, by performing linear regressions of the values of beyond-accuracy metrics on the values of NDCG for the optimal hyperparameter configurations, we quantify the interplay of accuracy and beyond-accuracy metrics in terms of the the slope of the lines of best fit. Furthermore, by performing experiments in the domains of movie rating, music streaming, and food and household delivery and with four recommendation algorithms we provide insight in the generalizability of the interplay between accuracy and beyond-accuracy metrics. Our analysis shows that for 8 out of 12 combinations of algorithms and domains, the line of best fit for at least one beyond-accuracy metric has a negative slope, indicating a trade-off relationship and supporting the multiobjective hyperparameter optimization.  Our analysis further shows that both the sign and the absolute value of the slope of the line of best fit depend on the recommendation algorithm as well as the  recommendation domain, indicating the non-generalizability of the interplay between accuracy and beyond-accuracy metrics in the hyperparameter optimization." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://ceur-ws.org/Vol-3476/paper3.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: MultiObjectiveHyperOpt
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_PerspectivesRecSys_MultiObjectiveHyperOpt.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2023_PerspectivesRecSys_MultiObjectiveHyperOpt.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- moscati
- Deldjoo, Yashar
- Carparelli, Giulio Davide
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CEUR Workshop Proceedings
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: proceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 3rd Workshop on Perspectives on the Evaluation of Recommender Systems co-located with the 17th ACM Conference on Recommender Systems (RecSys 2023), Singapore, Singapore. 
  editor: Said, Alan and Zangerle, Eva and Bauer, Christine
  publisher: CEUR-WS.org
  address: 
  doi:		
  url: https://ceur-ws.org/Vol-3476/paper3.pdf
  volume: 3476
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
preview-youtube-id: fTTh4rMeUCQ

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: recsyslearn Library
#  # use link instead of abslink if you want to link to the master directory
  abslink: https://recsyslearn.readthedocs.io/en/latest/
#  # defaults to a download icon, use this if you want a link-out icon
  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/mmosc/moho

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

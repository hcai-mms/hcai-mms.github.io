---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Networked Tastes: Homophily for Music Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Many recommender systems implicitly assume homophily, i.e., that socially connected users have similar tastes. This assumption can be particularly problematic in group recommendation settings, where individuals' preferences can be non-homogeneous. Our study examines the homophily assumption in the music domain. Leveraging techniques from network analysis, we reconsider the definition of music similarity and analyze how users' taste similarity relates to social network structures across multiple levels. We then carry out recommendation experiments to evaluate how incorporating information on user--artist interactions, user--user connections, and artist--artist similarity, affects the quality of music recommendations. Our findings show that homophily operates differently across granularities, with a limited artist-level similarity among connected users, and a higher similarity at the artist-cluster level, and that different user groups benefit differently from the inclusion of social network and artist similarity data in recommendation quality. The results challenge homophily as a uniformly reliably proxy for inferring music preferences and suggest that a multi-granular, multi-layer notion of similarity better accounts for preference heterogeneity in group recommendations settings."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://ceur-ws.org/Vol-3476/paper3.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: group_homophily
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2026_06_GMAP_UMAP.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2026_06_GMAP_UMAP.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- moscati
- Xu, Xinwei
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CEUR Workshop Proceedings
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2026

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://ceur-ws.org/Vol-xxxx/ # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: proceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Workshops Proceedings of the 34th ACM International Conference on User Modeling, Adaptation and Personalization (UMAP 2026), Gothenburg, Sweden. 
  editor: 
  publisher: CEUR-WS.org
  address: 
  doi:		
  # url: https://ceur-ws.org/Vol-xxxx/
  # volume: 4045
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
# youtube-id:
# the youtube-id of the preview-video
# preview-youtube-id: fTTh4rMeUCQ

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: /assets/pdf/2026_06_GMAP_UMAP.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
# supplements:
# - name: Dashboard
#  # use link instead of abslink if you want to link to the master directory
  # abslink: 
#  # defaults to a download icon, use this if you want a link-out icon
  # linksym: true

# Link to the repository where the code is hostet
code: https://github.com/hcai-mms/homophily

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

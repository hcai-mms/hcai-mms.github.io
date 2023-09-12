---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Computational Versus Perceived Popularity Miscalibration in Recommender Systems" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Popularity bias in recommendation lists refers to over-representation of popular content and is a challenge for many recommendation algorithms. Previous research has suggested several offline metrics to quantify popularity bias, which commonly relate the popularity of items in users' recommendation lists to the popularity of items in their interaction history. Discrepancies between these two factors are referred to as popularity miscalibration. While popularity metrics provide a straightforward and well-defined means to measure popularity bias, it is unknown whether they actually reflect users' perception of popularity bias.To address this research gap, we conduct a crowd-sourced user study on Prolific, involving 56 participants, to (1) investigate whether the level of perceived popularity miscalibration differs between common recommendation algorithms, (2) assess the correlation between perceived popularity miscalibration and its corresponding quantification according to a common offline metric. We conduct our study in a well-defined and important domain, namely music recommendation using the standardized LFM-2b dataset, and quantify popularity miscalibration of five recommendation algorithms by utilizing Jensen-Shannon distance (JSD). Challenging the findings of previous studies, we observe that users generally do perceive significant differences in terms of popularity bias between algorithms if this bias is framed as popularity miscalibration. In addition, JSD correlates moderately with users' perception of popularity, but not with their perception of unpopularity." 
# insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: CompVsUserPercep
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_sigir_lesota_compvspercep.jpeg
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2023_sigir_lesota_compvspercep_teaser.jpeg

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- lesota
- escobedo-ticona
- Deldjoo, Yashar 
- Ferwerda, Bruce 
- Kopeinik, Simone 
- Lex, Elisabeth
- rekab-saz
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: SIGIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://doi.org/10.1145/3539618.3591964 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  location: Taipei, Taiwan
  doi: 10.1145/3539618.3591964		# e.g.10.1109/TVCG.2020.3012063
  url: https://doi.org/10.1145/3539618.3591964
  volume: 
  number: 
  pages: 1889--1893
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

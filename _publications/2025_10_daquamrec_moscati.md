---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Single-Branch Architectures for Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Single-branch architectures have been proven effective for several multimodal learning tasks. In this talk, after reviewing the use of single-branch architectures in multimodal learning, I describe their use in multimodal recommendation, showing how they allow to address missing-modality and cold-start scenarios. I then describe the use of single-branch architectures in collaborative filtering, showing how they allow to reduce the number of model parameters without substantially affecting the quality of recommendations."

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://ceur-ws.org/Vol-3476/paper3.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: daquamrec_single
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_TORS_SiBraR.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_TORS_SiBraR.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- moscati

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CEUR Workshop Proceedings
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://ceur-ws.org/Vol-4188/ # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: proceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the DaQuaMRec 2025 Workshop on Data Quality-Aware Multimodal Recommendation co-located with RecSys 2025, Prague, Czech Republic. 
  editor: Pomo, Claudio and Jannach, Dietmar and Kim, Yubin and Malitesta, Daniele and Mancino, Alberto Carlo Maria and McAuley, Julian and Melchiorre, Alessandro and Nawaz, Shah
  publisher: CEUR-WS.org
  address: 
  doi:		
  url: https://ceur-ws.org/Vol-4188/
  volume: 4188
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
pdf: /assets/pdf/2025_10_daquamrec_moscati.pdf
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
# code: https://github.com/hcai-mms/multimodal_mir

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

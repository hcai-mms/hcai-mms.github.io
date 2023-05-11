---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Music4All-Onion -- A Large-Scale Multi-Faceted Content-Centric Music Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "When we appreciate a piece of music, it is most naturally because of its content, including rhythmic, tonal, and timbral elements as well as its lyrics and semantics. This suggests that the human affinity for music is inherently content-driven. This kind of information is, however, still frequently neglected by mainstream recommendation models based on collaborative filtering that rely solely on user-item interactions to recommend items to users. A major reason for this neglect is the lack of standardized datasets that provide both collaborative and content information. The work at hand addresses this shortcoming by introducing Music4All-Onion, a large-scale, multi-modal music dataset. The dataset expands the Music4All dataset by including 26 additional audio, video, and metadata characteristics for 109,269 music pieces. In addition, it provides a set of 252,984,396 listening records of 119,140 users, extracted from the online music platform Last.fm, which allows leveraging user-item interactions as well. We organize distinct item content features in an onion model according to their semantics, and perform a comprehensive examination of the impact of different layers of this model (e.g., audio features, user-generated content, and derivative content) on content-driven music recommendation, demonstrating how various content features influence accuracy, novelty, and fairness of music recommendation systems. In summary, with Music4All-Onion, we seek to bridge the gap between collaborative filtering music recommender systems and content-centric music recommendation requirements." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: # https://dl.acm.org/doi/abs/10.1145/3511808.3557656
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: Music4AllOnion
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2022_cikm_onion.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2022_cikm_onion.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- moscati
- parada-cabaleiro
- deldjoo
- zangerle
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CIKM
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2022

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 31st ACM International Conference on Information & Knowledge Management (CIKM)
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  doi:		10.1145/3511808.
  url:  https://doi.org/10.1145/3511808.3557656
  volume: 
  number: 
  pages: 4339–4343
  month: 
  location: Atlanta, GA, USA

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
pdf: /assets/pdf/2022_cikm_onion.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
code: 

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

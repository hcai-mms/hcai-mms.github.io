---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Music4All A+A: A Multimodal Dataset for Music Information Retrieval Tasks" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Music is characterized by aspects related to different modalities, such as the audio signal, the lyrics, or the music video clips. This has motivated the development of multimodal datasets and methods for Music Information Retrieval (MIR) tasks such as genre classification or autotagging. Music can be described at different levels of granularity, for instance defining genres at the level of artists or music albums. However, most datasets for multimodal MIR neglect this aspect and provide data at the level of individual music tracks. We aim to fill this gap by providing Music4All Artist and Album (Music4All A+A), a dataset for multimodal MIR tasks based on music artists and albums. Music4All A+A is built on top of the Music4All-Onion dataset, an existing track-level dataset for MIR tasks. Music4All A+A provides metadata, genre labels, image representations, and textual descriptors for 6,741 artists and 19,511 albums. Furthermore, since Music4All A+A is built on top of Music4All-Onion, it allows access to other multimodal data at the track level, including user--item interaction data. This renders Music4All A+A suitable for a broad range of MIR tasks, including multimodal music recommendation, at several levels of granularity. To showcase the use of Music4All A+A, we carry out experiments on multimodal genre classification of artists and albums, including an analysis in missing-modality scenarios, and a quantitative comparison with genre classification in the movie domain. Our experiments show that images are more informative for classifying the genres of artists and albums, and that several multimodal models for genre classification struggle in generalizing across domains. We provide the code to reproduce our experiments at this https URL, the dataset is linked in the repository and provided open-source under a CC BY-NC-SA 4.0 license. " # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://arxiv.org/abs/2509.14891
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: music4all
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_music4all.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_music4all.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Jonas Geiger
- moscati
- nawaz
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CBMI
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  journal: International Journal of Multimedia Information Retrieval # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: "CBMI '25: Proceedings of the 22nd International Conference on Content-based Multimedia Indexing"
  editor: 
  publisher: 
  address: 
  doi: 10.48550/arXiv.2509.14891
  url: https://doi.org/
  volume: 
  number: 
  pages: 
  month: 

preprint:	https://arxiv.org/abs/2509.14891 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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
code: https://github.com/hcai-mms/Music4All-A-A

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

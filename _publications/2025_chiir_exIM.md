---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "ExIM: Exploring Intent of Music Listening for Retrieving User-generated Playlists" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Music psychology has identified various reasons why people listen to music, based on empirical evidence from interviews and surveys. In this paper, we take a data-driven approach that adopts both pre-trained Sentence Transformers and Cross Encoder, as well as graph-based clustering to first determine music listening intents and then explore user-generated playlists by comparing the title to the listening intents. For this purpose, we first investigated whether 129 established listening functions, previously identified by Schäfer et al. (2013), could be meaningfully clustered into broader listening intents. While Schäfer et al. (2013) introduced three broad dimensions of music listening, this work aimed to identify smaller, context-specific intents to capture more nuanced intents. The resulting clusters were then evaluated through a first survey to select the clusters of the best performing model. In a second survey, music listening intent clusters were explored in more detail to obtain a deeper understanding of their significance for music retrieval and recommendation. Lastly, the playlist selection per intent and characteristics of different listening intents were further explored through a third survey. Given the encouraging results of the evaluation of the computed clusters (92% of clusters judged consistent by participants) and the insight that more than half of the participants search for playlists for a specific intent, we propose a browsing system that categorizes playlists based on their intent and enables users to explore similar playlists. Our approach is further visualized in a dashboard to explore and browse through playlists in intent space."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://aclanthology.org/2024.emnlp-main.612.pdf # https://aclanthology.org/2024.emnlp-main.612.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: chiir_exim
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_chiir_exIM.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- hausberger
- Strauss, Hannah
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CHIIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: CHIIR'25: Proceedings of the 2025 ACM SIGIR Conference on Human Information Interaction and Retrieval 
  editor: # George Buchanan, Haiming Liu, Dana McKAy, Douglas Oard
  publisher: Association for Computing Machinery
  address: New York, NY, United States
  doi: 10.1145/3698204.3716470
  url: https://chiir2025.github.io/
  volume: 
  number: 
  pages: 348-357
  month: April
  location: Melbourne, Australia

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
# pdf: /assets/pdf/2024_recsys_sibrar.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
# supplement: /assets/pdf/2024_recsys_supplementar.pdf

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

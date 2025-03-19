---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "The impact of playlist characteristics on coherence in user-curated music playlists" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Music playlist creation is a crucial, yet not fully explored task in music data mining and music information retrieval. Previous studies have largely focused on investigating diversity, popularity, and serendipity of tracks in human- or machine-generated playlists. However, the concept of playlist coherence – vaguely defined as smooth transitions between tracks – remains poorly understood and even lacks a standardized definition. In this paper, we provide a formal definition for measuring playlist coherence based on the sequential ordering of tracks, offering a more interpretable measurement compared to existing literature, and allowing for comparisons between playlists with different musical styles. The presented formal framework to measure coherence is applied to analyze a substantial dataset of user-generated playlists, examining how various playlist characteristics influence coherence. We identified four key attributes: playlist length, number of edits, track popularity, and collaborative playlist curation as potential influencing factors. Using correlation and causal inference models, the impact of these attributes on coherence across ten auditory and one metadata feature are assessed. Our findings indicate that these attributes influence playlist coherence to varying extents. Longer playlists tend to exhibit higher coherence, whereas playlists dominated by popular tracks or those extensively modified by users show reduced coherence. In contrast, collaborative playlist curation yielded mixed results. The insights from this study have practical implications for enhancing recommendation tasks, such as automatic playlist generation and continuation, beyond traditional accuracy metrics. As a demonstration of these findings, we propose a simple greedy algorithm that reorganizes playlists to align coherence with observed trends." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://link.springer.com/article/10.1140/epjds/s13688-025-00531-3
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: ImpactPlay
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- schweiger
- parada-cabaleiro
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: EPJ-DS
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: EPJ Data Science # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 10.1140/epjds/s13688-025-00531-3		
  url: https://doi.org/10.1140/epjds/s13688-025-00531-3
  volume: 14
  number: 
  pages: 24
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

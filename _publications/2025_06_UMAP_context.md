---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Why Context Matters: Exploring How Musical Context Impacts User Behavior, Mood, and Musical Preferences" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Music consumption is shaped by both internal factors (e.g., mood, motivation) and external factors (e.g., activity, social environment), which together influence listeners’ behavior (e.g., focus, songs’ skips) and reactions (e.g., mood changes). While prior research has explored real-life or survey-based, context-aware music listening with limited available context information, we introduce a dataset comprising 216 music listening sessions collected in real-world settings through a custom-built Android mobile application designed to assess a wide range of contextual factors. The dataset captures static (e.g., activity, social environment, motivation) and dynamic (e.g., mood changes) contextual factors, along with music interaction data (e.g., skipped or fully listened songs), listening focus levels, and participant traits (e.g., demographics, music education, listening preferences, personality). Our analysis highlights key insights into how different contextual factors influence user behavior and mood. demonstrating significant differences in skipping songs, focus levels, and genre diversity. We show that music listening sessions grouped by context are significantly different in terms of music listening behaviors (focus, skipping, and session genre diversity) and mood changes (happiness, sadness, stress, and energy). Furthermore, we explore the correlations between personality traits and listening behaviors (mean skip rate and genre diversity). Ultimately, our findings emphasize the importance of understanding context, as different situations lead to distinct music preferences and have varying impacts on user behavior and emotional responses."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://dl.acm.org/doi/10.1145/3699682.3728354 # https://dl.acm.org/doi/abs/10.1145/3511808.3557656
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: context
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_context.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_context.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- hausberger
- Emilia Parada-Cabaleiro
- schedl


# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: UMAP
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 33nd ACM Conference on User Modeling, Adaptation and Personalization (UMAP)
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  doi: 10.1145/3699682.3728354
  url:  
  volume: 
  number: 
  pages: 
  month: 
  location: 

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
# pdf:
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
# supplement: 

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

---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Listener Modeling and Context-Aware Music Recommendation Based on Country Archetypes" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Music preferences are strongly shaped by the cultural and socio-economic background of the listener, which is reflected, to a considerable extent, in country-specific music listening profiles. Previous work has already identified several country-specific differences in the popularity distribution of music artists listened to. In particular, what constitutes the “music mainstream” strongly varies between countries. To complement and extend these results, the article at hand delivers the following major contributions: First, using state-of-the-art unsupervized learning techniques, we identify and thoroughly investigate (1) country profiles of music preferences on the fine-grained level of music tracks (in contrast to earlier work that relied on music preferences on the artist level) and (2) country archetypes that subsume countries sharing similar patterns of listening preferences. Second, we formulate four user models that leverage the user’s country information on music preferences. Among others, we propose a user modeling approach to describe a music listener as a vector of similarities over the identified country clusters or archetypes. Third, we propose a context-aware music recommendation system that leverages implicit user feedback, where context is defined via the four user models. More precisely, it is a multi-layer generative model based on a variational autoencoder, in which contextual features can influence recommendations through a gating mechanism. Fourth, we thoroughly evaluate the proposed recommendation system and user models on a real-world corpus of more than one billion listening records of users around the world (out of which we use 369 million in our experiments) and show its merits vis-à-vis state-of-the-art algorithms that do not exploit this type of context information." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://www.frontiersin.org/articles/10.3389/frai.2020.508725
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: ListenerModeling
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2021_fai_listenermodeling.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2021_fai_listenermodeling_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- schedl
- Bauer, Christine
- Reisinger, Wolfgang
- Kowald, Dominik
- Lex, Elisabeth

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: Frontiers in Artificial Intelligence
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2021

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: 

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Frontiers in Artificial Intelligence # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  editor: 
  publisher: 
  address: 
  doi: 10.3389/frai.2020.508725		# e.g.10.1109/TVCG.2020.3012063
  url: https://www.frontiersin.org/articles/10.3389/frai.2020.508725
  volume: 3
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






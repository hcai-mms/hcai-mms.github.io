---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Personality Correlates of Music Audio Preferences for Modelling Music Listeners" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Past studies have shown that personality has a significant association with user behaviour and preferences, not least towards music. This makes personality information a promising aspect for user modelling in personalised recommender systems and similar domains. In contrast to existing studies, which investigate personality correlates of music preferences via genres or styles, we study such correlates by modelling music preferences at a finer-grained content level, using audio features of the music users listen to. Leveraging listening and personality information of more than 1,300 Last.fm users, we identify several significant medium and weak correlations between music audio features and personality traits, the latter defined by the five-factor model. Our results provide useful insights into the relationship between personality and music preference, which can be valuable for music recommender systems in terms of more personalised recommendations." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: # https://dl.acm.org/doi/abs/10.1145/3340631.3394874
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: PersonalityCorrelates
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2020_umap_perscorr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2020_umap_perscorr.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- melchiorre
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: UMAP
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2020

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 28th ACM Conference on User Modeling, Adaptation and Personalization (UMAP)
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  doi:	10.1145/3340631.3394874
  url:  https://doi.org/10.1145/3340631.3394874
  volume: 
  number: 
  pages: 313–-317
  month: 
  location: Virtual Event, Genoa, Italy

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
youtube-id: 6ZiXgVX4J0o&t=3s
# the youtube-id of the preview-video
preview-youtube-id: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: /assets/pdf/2020_umap_perscorr.pdf
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
code: https://gitlab.cp.jku.at/alessandro/pers-corr

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


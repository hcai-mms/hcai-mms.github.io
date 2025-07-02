---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Familiarizing with Music: Discovery Patterns for Different Music Discovery Needs" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Humans have the tendency to discover and explore. This natural tendency is reflected in data from streaming platforms as the amount of previously unknown content accessed by users. Additionally, in domains such as that of music streaming there is evidence that recommending novel content improves users’ experience with the platform. Therefore, understanding users’ discovery patterns, such as the amount to which and the way users access previously unknown content, is a topic of relevance for both the scientific community and the streaming industry, particularly the music one. Previous works studied how music consumption differs for users of different traits and looked at diversity, novelty, and consistency over time of users’ music preferences. However, very little is known about how users discover and explore previously unknown music, and how this behavior differs for users of varying discovery needs. In this paper we bridge this gap by analyzing data from a survey answered by users of the major music streaming platform Deezer in combination with their streaming data. We first address questions regarding whether users who declare a higher interest in unfamiliar music listen to more diverse music, have more stable music preferences over time, and explore more music within a same time window, compared to those who declare a lower interest. We then investigate which type of music tracks users choose to listen to when they explore unfamiliar music, identifying clear patterns of popularity and genre representativeness that vary for users of different discovery needs.
Our findings open up possibilities to infer users’ interest in unfamiliar music from streaming data as well as possibilities to develop recommender systems that guide users in exploring music in a more natural way."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://aclanthology.org/2024.emnlp-main.612.pdf # https://aclanthology.org/2024.emnlp-main.612.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: UMAP_discoveryPattern
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: placeholder.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- moscati
- Afchar Darius
- schedl
- Sguerra Bruno

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
  booktitle: "Proceedings of the 33rd ACM Conference on User Modeling, Adaptation and Personalization" 
  editor: # George Buchanan, Haiming Liu, Dana McKAy, Douglas Oard
  publisher: Association for Computing Machinery
  address: 
  doi: https://doi.org/10.1145/3699682.3728333
  url: https://dl.acm.org/doi/proceedings/10.1145/3699682
  volume: 
  number: 
  pages: 63-73
  month: June
  location: New York, NY, United States 

preprint:	 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: Best Reviewer Award

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

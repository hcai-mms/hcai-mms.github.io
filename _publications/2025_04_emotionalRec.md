---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Nuanced Music Emotion Recognition via a Semi-Supervised Multi-Relational Graph Neural Network" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Music emotion recognition (MER) seeks to understand the complex emotional landscapes elicited by music, acknowledging music’s profound social and psychological roles beyond traditional tasks such as genre classification or content similarity. MER relies heavily on high‑quality emotional annotations, which serve as the foundation for training models to recognize emotions. However, collecting these annotations is both complex and costly, leading to limited availability of large‑scale datasets for MER. Recent efforts in MER for automatically extracting emotion have focused on learning track representations in a supervised manner. However, these approaches mainly use simplified emotion models due to limited datasets or a lack of necessity for sophisticated emotion models and ignore hidden inter‑track relations, which are beneficial in a semi‑supervised learning setting. This paper proposes a novel approach to MER by constructing a multi‑relational graph that encapsulates different facets of music. We leverage graph neural networks to model intricate inter‑track relationships and capture structurally induced representations from user data, such as listening histories, genres, and tags. Our model, the semi‑supervised multi‑relational graph neural network for emotion recognition (SRGNN‑Emo), innovates by combining graph‑based modeling with semi‑supervised learning, using rich user data to extract nuanced emotional profiles from music tracks. Through extensive experimentation, SRGNN‑Emo demonstrates significant improvements in R2 and root mean squared error metrics for predicting the intensity of nine continuous emotions (Geneva Emotional Music Scale), demonstrating its superior capability in capturing and predicting complex emotional expressions in music."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://aclanthology.org/2024.emnlp-main.612.pdf # https://aclanthology.org/2024.emnlp-main.612.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: emotional_rec
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_emotional_rec.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_emotional_rec.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Peintner, Andreas
- moscati
- Kinoshita, Yu
- Vogl, Richard
- Knees, Peter
- schedl
- Strauss, Hannah
- Zenter, Marcel
- Zangerle, Eva

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ISMIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: "Transactions of the International Society for Music Information Retrieval" 
  editor: # George Buchanan, Haiming Liu, Dana McKAy, Douglas Oard
  publisher: Association for Computing Machinery
  address: 
  doi: 10.5334/tismir.235
  url: https://transactions.ismir.net/
  volume: 8
  number: 
  pages: 140-153
  month: April
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

---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Just Ask for Music (JAM): Multimodal and Personalized Natural Language Music Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Natural language interfaces offer a compelling approach for music recommendation, enabling users to express complex preferences conversationally. While Large Language Models (LLMs) show promise in this direction, their scalability in recommender systems is limited by high costs and latency. Retrieval-based approaches using smaller language models mitigate these issues but often rely on single-modal item representations, overlook long-term user preferences, and require full model retraining, posing challenges for real-world deployment. In this paper, we present JAM (Just Ask for Music), a lightweight and intuitive framework for natural language music recommendation. JAM models user–query–item interactions as vector translations in a shared latent space, inspired by knowledge graph embedding methods like TransE. To capture the complexity of music and user intent, JAM aggregates multimodal item features via cross-attention and sparse mixture-of-experts. We also introduce JAMSessions, a new dataset of over 100k user–query–item triples with anonymized user/item embeddings, uniquely combining conversational queries and user long-term preferences. Our results show that JAM provides accurate recommendations, produces intuitive representations suitable for practical use cases, and can be easily integrated with existing music recommendation stacks." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://dl.acm.org/doi/10.1145/3705328.3748020
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: JAM
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_recsys_Melchiorre_JAM_.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_recsys_Melchiorre_JAM_.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- melchiorre
- Epure, Elena V. 
- masoudian
- escobedo-ticona
- hausberger
- Moussallam, Manuel 
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: RECSYS
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  journal:  # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the Nineteenth ACM Conference on Recommender Systems
  editor: 
  publisher: ACM
  address: 
  doi: 10.1145/3705328.3748020
  url: https://doi.org/10.1145/3705328.3748020
  volume: 
  number: 
  pages: 615-620
  month: September

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


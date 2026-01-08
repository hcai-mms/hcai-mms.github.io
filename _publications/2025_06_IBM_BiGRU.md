---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Development of a bilingual healthcare chatbot for pregnant women: A comparative study of deep learning models with BiGRU optimization" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "With the growing demand for healthcare services and a persistent shortage of medical professionals, intelligent systems such as chatbots are gaining relevance in improving patient support. In obstetrics, pregnant women require fast, accessible, and reliable information to monitor their health and the progression of their pregnancy. This study aims to design and evaluate a bilingual chatbot tailored to the healthcare needs of pregnant women, leveraging recent advances in deep learning for natural language processing (NLP). We developed and compared five deep learning architectures – artificial neural networks (ANN), long short-term memory (LSTM), bidirectional LSTM (BiLSTM), gated recurrent units (GRU), and bidirectional GRU (BiGRU) – to identify the most suitable model for chatbot implementation. Each model was trained on a bilingual dataset of pregnancy-related questions and answers, and evaluated using accuracy, computational efficiency, and contextual relevance of responses. The BiGRU model achieved the highest performance, demonstrating superior accuracy and response efficiency over the other models. It consistently delivered context-aware, personalized answers in both languages, showing its robustness in handling sequential healthcare queries. These findings suggest that BiGRU networks offer a promising solution for building intelligent, bilingual healthcare chatbots aimed at supporting pregnant women. Future work will focus on expanding the dataset, incorporating voice-based input, and deploying the chatbot in real-world healthcare settings for clinical validation." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://doi.org/10.1016/j.ibmed.2025.100261
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: BiGRU
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_BiGRU.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_BiGRU.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Ablavi Ericka Armela
- Nabila Zrira
- Khadija Ouazzani-Touhami
- Haris Ahmad Khan
- nawaz

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: 
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: IEEE International Conference on Content-Based Multimedia Indexing # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: "Intelligence-Based Medicine"
  editor: 
  publisher: 
  address: 
  doi: 
  url: 
  volume: 
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
- name: 
#  # use link instead of abslink if you want to link to the master directory
  abslink: 
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: 

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

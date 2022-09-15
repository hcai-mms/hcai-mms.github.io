---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Affect in Multimedia: Benchmarking Violent Scenes Detection" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "In this article, we report on the creation of a publicly available, common evaluation framework for Violent Scenes Detection (VSD) in Hollywood and YouTube videos. We propose a robust data set, the VSD96, with more than 96 hours of video of various genres, annotations at different levels of detail (e.g., shot-level, segment-level), annotations of mid-level concepts (e.g., blood, fire), various pre-computed multi-modal descriptors, and over 230 system output results as baselines. This is the most comprehensive data set available to this date tailored to the VSD task and was extensively validated during the MediaEval benchmarking campaigns. Furthermore, we provide an in-depth analysis of the crucial components of VSD algorithms, by reviewing the capabilities and the evolution of existing systems (e.g., overall trends and outliers, the influence of the employed features and fusion techniques, the influence of deep learning approaches). Finally, we discuss the possibility of going beyond state-of-the-art performance via an ad-hoc late fusion approach. Experimentation is carried out on the VSD96 data. We provide the most important lessons learned and gained insights. The increasing number of publications using the VSD96 data underline the importance of the topic. The presented and published resources are a practitioner's guide and also a strong baseline to overcome, which will help researchers for the coming years in analyzing aspects of audio-visual affect and violence detection in movies and videos." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: AffectMult
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2022_ieee_affectmultimedia.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2022_ieee_affectmultimedia_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Constantin, Mihai Gabriel 
- Ştefan, Liviu-Daniel 
- Ionescu, Bogdan 
- Demarty, Claire-Hélène 
- Sjöberg, Mats 
- schedl
- Gravier, Guillaume 

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: IEEE TAC
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2022

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: IEEE Transactions on Affective Computing # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi:	10.1109/TAFFC.2020.2986969	# e.g.10.1109/TVCG.2020.3012063
  url: 
  volume: "13"
  number: "1"
  pages: "347-366"
  month: Jan

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


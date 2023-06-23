---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Parameter-efficient Modularised Bias Mitigation via AdapterFusion" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Large pre-trained language models contain societal biases and carry along these biases to downstream tasks. Current in-processing bias mitigation approaches (like adversarial training) impose debiasing by updating a model’s parameters, effectively transferring the model to a new, irreversible debiased state. In this work, we propose a novel approach to develop stand-alone debiasing functionalities separate from the model, which can be integrated into the model on-demand, while keeping the core model untouched. Drawing from the concept of AdapterFusion in multi-task learning, we introduce DAM (Debiasing with Adapter Modules) – a debiasing approach to first encapsulate arbitrary bias mitigation functionalities into separate adapters, and then add them to the model on-demand in order to deliver fairness qualities. We conduct a large set of experiments on three classification tasks with gender, race, and age as protected attributes. Our results show that DAM improves or maintains the effectiveness of bias mitigation, avoids catastrophic forgetting in a multi-attribute scenario, and maintains on-par task performance, while granting parameter-efficiency and easy switching between the original and debiased models." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: DAM_EACL_2023
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_eacl_dam.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2023_eacl_dam_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- kumar
- lesota
- Zerveas, George 
- Cohen, Daniel
- Eickoff, Carsten
- schedl
- rekab-saz

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: EACL
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://aclanthology.org/2023.eacl-main.201 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 17th Conference of the European Chapter of the Association for Computational Linguistics
  editor: 
  publisher: Association for Computational Linguistics
  address: Dubrovnik, Croatia
  location:
  doi:		# e.g.10.1109/TVCG.2020.3012063
  url: https://aclanthology.org/2023.eacl-main.201
  volume:
  number: 
  pages: 2738–2751
  month: May

preprint:	https://arxiv.org/abs/2302.06321 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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
# pdf: /assets/pdf/ProtoMF__Prototype_based_Matrix_Factorization.pdf
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
code: https://github.com/CPJKU/ModularizedDebiasing-private/tree/ModularizedDebiasing-public

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

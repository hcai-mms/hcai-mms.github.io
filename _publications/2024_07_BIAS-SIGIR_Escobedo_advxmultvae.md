---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Simultaneous Unlearning of Multiple Protected User Attributes From Variational Autoencoder Recommenders Using Adversarial Training" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "In widely used neural network-based collaborative filtering models, users’ history logs are encoded into latent embeddings that represent the users’ preferences. In this setting, the models are capable of mapping users’ protected attributes (e.g., gender or ethnicity) from these user embeddings even without explicit access to them, resulting in models that may treat specific demographic user groups unfairly and raise privacy issues. While prior work has approached the removal of a single protected attribute of a user at a time, multiple attributes might come into play in real-world scenarios. In the work at hand, we present AdvXMultVAE which aims to unlearn multiple protected attributes (exemplified by gender and age) simultaneously to improve fairness across demographic user groups. For this purpose, we couple a variational autoencoder (VAE) architecture with adversarial training (AdvMultVAE) to support simultaneous removal of the users’ protected attributes with continuous and/or categorical values. Our experiments on two datasets, LFM-2b-100k and Ml-1m, from the music and movie domains, respectively, show that our approach can yield better results than its singular removal counterparts (based on AdvMultVAE) in effectively mitigating demographic biases whilst improving the anonymity of latent embeddings."
 # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: advx-multvae
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2024_07_BIAS-SIGIR_Escobedo_advxmultvae.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2024_07_BIAS-SIGIR_Escobedo_advxmultvae.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- escobedo-ticona
- ganhoer
- brandl
- Augstein, Mirjam 
- schedl
# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: BIAS@SIGIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl:  # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: "Proceedings of the 5th International Workshop on Algorithmic Bias in Search and Recommendation (BIAS @ SIGIR 2024)"
  editor: 
  publisher: 
  address: 
  location: Washington D.C., USA
  doi:		
  url: 
  volume: 
  number: 
  pages: 
  month: July

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
code: 
github: https://github.com/hcai-mms/advx-multvae
# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Effective Controllable Bias Mitigation for Classification and Retrieval using Gate Adapters" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Bias mitigation of Language Models has been the topic of many studies with a recent focus on learning separate modules like adapters for on-demand debiasing. Besides optimizing for a modularized debiased model, it is often critical in practice to control the degree of bias reduction at inference time, e.g., in order to tune for a desired performance-fairness trade-off in search results or to control the strength of debiasing in classification tasks. In this paper, we introduce Controllable Gate Adapter (ConGater), a novel modular gating mechanism with adjustable sensitivity parameters, which allows for a gradual transition from the biased state of the model to the fully debiased version at inference time. We demonstrate ConGater performance by (1) conducting adversarial debiasing experiments with three different models on three classification tasks with four protected attributes, and (2) reducing the bias of search results through fairness list-wise regularization to enable adjusting a trade-off between performance and fairness metrics. Our experiments on the classification tasks show that compared to baselines of the same caliber, ConGater can maintain higher task performance while containing less information regarding the attributes. Our results on the retrieval task show that the fully debiased ConGater can achieve the same fairness performance while maintaining more than twice as high task performance than recent strong baselines. Overall, besides strong performance ConGater enables the continuous transitioning between biased and debiased states of models, enhancing personalization of use and interpretability through controllability. " # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: ConGater_EACL_2024
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2024_EACL_ConGaterW.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
# image_large: 

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- masoudian
- Cornelia, Volaucnik
- schedl 
- rekab-saz 

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: EACL
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl:  # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: The 18th Conference of the European Chapter of the Association for Computational Linguistics March 17-22, 2024
  editor: 
  publisher: 
  address: 
  location: Malta
  doi:		
  url: 
  volume: 18th
  number: 
  pages: 
  month: March 17-22

preprint:	https://arxiv.org/pdf/2401.16457.pdf # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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
code: https://github.com/ShawMask/congater_dcase2022t1

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

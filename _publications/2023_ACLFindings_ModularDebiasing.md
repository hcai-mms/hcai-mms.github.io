---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Modular and On-demand Bias Mitigation with Attribute-Removal Subnetworks" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Societal biases are reflected in large pre-trained language models and their fine-tuned versions on downstream tasks. Common in-processing bias mitigation approaches, such as adversarial training and mutual information removal, introduce additional optimization criteria, and update the model to reach a new debiased state. However, in practice, end-users and practitioners might prefer to switch back to the original model, or apply debiasing only on a specific subset of protected attributes. To enable this, we propose a novel modular bias mitigation approach, consisting of stand-alone highly sparse debiasing subnetworks, where each debiasing module can be integrated into the core model on-demand at inference time. Our approach draws from the concept of diff pruning, and proposes a novel training regime adaptable to various representation disentanglement optimizations. We conduct experiments on three classification tasks with gender, race, and age as protected attributes. The results show that our modular approach, while maintaining task performance, improves (or at least remains on-par with) the effectiveness of bias mitigation in comparison with baseline finetuning. Particularly on a two-attribute dataset, our approach with separately learned debiasing subnetworks shows effective utilization of either or both the subnetworks for selective bias mitigation." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: ModularDebiasing_ACLFindings_2023
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_ACLFindings_ModularDebiasing.png
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
- Hauzenberger, Lukas 
- masoudian
- kumar
- schedl  
- rekab-saz 

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ACLFindings
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl:  # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: "Findings of the Association for Computational Linguistics: ACL 2023"
  editor: 
  publisher: "Association for Computational Linguistics"
  address: 
  location: "Toronto, Canada"
  doi:	"10.18653/v1/2023.findings-acl.386"
  url: "https://aclanthology.org/2023.findings-acl.386"
  volume: 31st
  number: 
  pages: "6192--6214"
  month: July 2023

preprint:	https://arxiv.org/abs/2310.01217 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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

---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Modular Debiasing of Latent User Representations in Prototype-based Recommender Systems" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Recommender Systems (RSs) may inadvertently perpetuate biases based on protected attributes like gender, religion, or ethnicity. Left unaddressed, these biases can lead to unfair system behavior and privacy concerns. Interpretable RS models provide a promising avenue for understanding and mitigating such biases. In this work, we propose a novel approach to debias interpretable RS models by introducing user-specific scaling weights to the interpretable user representations of prototype-based RSs. This reduces the influence of the protected attributes on the RS’s prediction while preserving recommendation utility. By decoupling the scaling weights from the original representations, users can control the degree of invariance of recommendations to their protected characteristics. Moreover, by defining distinct sets of weights for each attribute, the user can further specify which attributes the recommendations should be agnostic to. We apply our method to ProtoMF, a state-of-the-art prototype-based RS model that models users by their similarities to prototypes. We employ two debiasing strategies to learn the scaling weights and conduct experiments on ML-1M and LFM2B-DB datasets aiming at making the user representations agnostic to age and gender. The results show that our approach effectively reduces the influence of the protected attributes on the representations on both datasets, showcasing flexibility in bias mitigation, while only marginally affecting recommendation quality. Finally, we assess the effects of the debiasing weights and provide qualitative evidence, particularly focusing on movie recommendations, of genre patterns identified by ProtoMF that correlate with specific genders."
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
shortname: ModDebias
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2024_09_ECMLPKDD_Melchiorre_ModDebias.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2024_09_ECMLPKDD_Melchiorre_ModDebias.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- melchiorre
- masoudian
- kumar 
- schedl
# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ECMLPKDD
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://link.springer.com/chapter/10.1007/978-3-031-70341-6_4  # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: "Proceedings of the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML PKDD 2024)"
  editor: 
  publisher: Springer
  address:  
  location:  Vilnius, Lithuania
  doi:	
  url: 
  volume: 
  number: 
  pages: 56--72
  month: September

preprint: # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: Best Student Paper Award

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
code: https://github.com/hcai-mms/modprotodebias

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

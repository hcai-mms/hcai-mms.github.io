---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "ProtoMF: Prototype-based Matrix Factorization for Effective and Explainable Recommendations" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Recent studies show the benefits of reformulating common machine learning models through the concept of prototypes -- representatives of the underlying data, used to calculate the prediction score as a linear combination of similarities of a data point to prototypes. Such prototype-based formulation of a model, in addition to preserving (sometimes enhancing) the performance, enables explainability of the model's decisions, as the prediction can be linearly broken down into the contributions of distinct definable prototypes. Following this direction, we extend the idea of prototypes to the recommender system domain by introducing ProtoMF, a novel collaborative filtering algorithm. ProtoMF learns sets of user/item prototypes that represent the general consumption characteristics of users/items in the underlying dataset. Using these prototypes, ProtoMF then represents users and items as vectors of similarities to the corresponding prototypes. These user/item representations are ultimately leveraged to make recommendations that are both effective in terms of accuracy metrics, and explainable through the interpretation of prototypes' contributions to the affinity scores. We conduct experiments on three datasets to assess both the effectiveness and the explainability of ProtoMF. Addressing the former, we show that ProtoMF exhibits higher Hit~Ratio and NDCG compared to other relevant collaborative filtering approaches. As for the latter, we qualitatively show how ProtoMF can provide explainable recommendations and how its explanation capabilities can expose the existence of statistical biases in the learned representations, which we exemplify for the case of gender bias." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: # https://dl.acm.org/doi/abs/10.1145/3523227.3546756
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: ProtoMF
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2022_recsys_protomf.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2022_recsys_protomf_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- melchiorre
- rekab-saz
- ganhoer
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: RecSys
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2022

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 16th ACM Conference on Recommender Systems (RecSys)
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  doi:		10.1145/3523227.3546756
  url:  https://doi.org/10.1145/3523227.3546756
  volume: 
  number: 
  pages: 246–-256
  month: 
  location: Seattle, WA, USA

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
pdf: /assets/pdf/2022_recsys_protomf.pdf
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
code: https://github.com/hcai-mms/ProtoMF

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


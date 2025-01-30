---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Single-Branch Network Architectures to Close the Modality Gap in Multimodal Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: thesis
abstract: "Traditional recommender systems rely on collaborative filtering (CF), using past user-item interactions to help users discover new items in a vast collection. In cold start, i.e., when interaction histories of users or items are unavailable, content-based recommender systems (CBRSs) use side information instead, most commonly, descriptions of items for item cold start. Hybrid recommender systems (HRSs) often employ multimodal learning to combine collaborative and user and item side information, which we jointly refer to as modalities. Though HRSs can provide recommendations when some modalities are missing, their quality degrades. In this work, we utilize single-branch neural networks equipped with weight sharing, modality sampling, and contrastive loss to provide accurate recommendations even in missing modality scenarios, including cold start, by closing the modality gap. We compare these networks with multi-branch alternatives and conduct extensive experiments on the MovieLens 1M, Music4All-Onion, and Amazon Video Games datasets. Six accuracy-based and four beyond-accuracy-based metrics help assess the recommendation quality and popularity bias for the different training paradigms and their hyperparameters on single- and multi-branch networks in warm-start and missing modality scenarios. We quantitatively and qualitatively study the effects of these different aspects on bridging the modality gap. Our results show that single-branch networks provide competitive recommendation quality in warm start, and a significantly better one in missing modality scenarios. Moreover, weight sharing, modality sampling, and contrastive loss lead to modalities of an item being closer together in embedding space than to other items."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: 
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True

institution: Johannes Kepler University Linz 
thesis_type: Master's Thesis
advisors : 
- schedl


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: master-thesis
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- ganhoer

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/obvulihs/content/titleinfo/11398151
# what is the publication type and other bib specific properties
bibentry: misc
bib:
  journal: # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  editor: 
  publisher: 
  address: 
  doi: 	# e.g.10.1109/TVCG.2020.3012063
  url: 
  volume: 
  number: 
  pages: 
  month:
  school: Johannes Kepler University Linz 

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





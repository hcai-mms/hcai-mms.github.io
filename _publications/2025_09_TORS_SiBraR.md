---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Single-Branch Network Architectures to Close the Modality Gap in Multimodal Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Traditional recommender systems rely on collaborative filtering (CF), using past user–item interactions to help users discover new items in a vast collection. In cold start, i. e., when interaction histories of users or items are not available, content-based recommender systems (CBRSs) use side information instead. Most commonly, user demographics and item descriptions are used for user and item cold start, respectively. Hybrid recommender systems (HRSs) often employ multimodal learning to combine collaborative and user and item side information, which we jointly refer to as modalities. Though HRSs can provide recommendations when some modalities are missing, their quality degrades. In this work, we utilize single-branch neural networks equipped with weight sharing, modality sampling, and contrastive loss to provide accurate recommendations even in missing modality scenarios, including cold start. Compared to multi-branch architectures, the weights of the encoding modules are shared for all modalities; in other words, all modalities are encoded using the same neural network. This, together with the contrastive loss, is essential in reducing the modality gap, while the modality sampling is essential in modeling missing modality during training. Simultaneously leveraging these techniques results in more accurate recommendations. We compare these networks with multi-branch alternatives and conduct extensive experiments on the MovieLens 1M, Music4All-Onion, and Amazon Video Games datasets. Six accuracy-based and four beyond-accuracy-based metrics help assess the recommendation quality for the different training paradigms and their hyperparameters on single- and multi-branch networks in warm-start and missing modality scenarios. We quantitatively and qualitatively study the effects of these different aspects on bridging the modality gap. Our results show that single-branch networks provide competitive recommendation quality in warm start, and significantly better performance in missing modality scenarios. Moreover, our study of modality sampling and contrastive loss on both single- and multi-branch architectures indicates a consistent positive impact on accuracy metrics across all datasets. Overall, the three training paradigms collectively encourage modalities of the same item to be embedded closer together than those of different items, as measured by Euclidean distance and cosine similarity. This results in embeddings that are less distinguishable and more interchangeable, as indicated by a 7-20% drop in modality prediction accuracy. Our full experimental setup, including training and evaluating code for all algorithms, their hyperparameter configurations, and our result analysis notebooks, is available at <a href=\"https://github.com/hcai-mms/single-branch-networks\">https://github.com/hcai-mms/single-branch-networks</a>.<br><br><h2>Training</h2><iframe width=\"560\" height=\"315\" src=\"https://www.youtube.com/embed/gh99n5hFFFo?si=L4XtXdwJXR8jb23J\" title=\"YouTube video player\" frameborder=\"0\" allow=\"accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share\" referrerpolicy=\"strict-origin-when-cross-origin\" allowfullscreen></iframe><br><br><h2>Inference</h2><iframe width=\"560\" height=\"315\" src=\"https://www.youtube.com/embed/GVtZ_TaPzsw?si=NihR0m7Dx_3zJ_xP\" title=\"YouTube video player\" frameborder=\"0\" allow=\"accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share\" referrerpolicy=\"strict-origin-when-cross-origin\" allowfullscreen></iframe>"
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://dl.acm.org/doi/10.1145/3604915.3608838 # https://dl.acm.org/doi/abs/10.1145/3511808.3557656
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: tors_sibrar
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_TORS_SiBraR.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_TORS_SiBraR.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- ganhoer
- moscati
- hausberger
- nawaz
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: TORS
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://dl.acm.org/doi/10.1145/3769430 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
key: Ganhoer2025TORS_SiBraR
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: ACM Transactions on Recommender Systems
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  url: https://doi.org/10.1145/3769430
  doi: 10.1145/3769430
  volume: 
  number: 
  pages: 
  month: 
  location:

preprint:	https://arxiv.org/abs/2509.18807 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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
# pdf: /assets/pdf/2024_recsys_sibrar.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
# supplement: /assets/pdf/2024_recsys_supplementar.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements: 
#- name: Medium Post
#  # use link instead of abslink if you want to link to the master directory
#  abslink: https://medium.com/@christian.ganhoer/a-brief-guide-on-sibrar-4a2476b5b73a
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
github: https://github.com/hcai-mms/single-branch-networks

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

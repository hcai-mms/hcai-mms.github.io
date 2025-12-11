---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Mitigating Latent User Biases in Pre-trained VAE Recommendation Models via On-demand Input Space Transformation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Recommender systems can unintentionally encode protected attributes (e.g., gender, country, or age) in their learned latent user representations. Current in-processing debiasing approaches, notably adversarial training, effectively reduce the encoded information on private user attributes. These approaches modify the model parameters during training. Thus, to alternate between biased and debiased model, two separate models have to be trained. In contrast, we propose a novel method to debias recommendation models post-training, which allows switching between biased and debiased model at inference time. Focusing on state-of-the-art variational autoencoder (VAE) architectures, our method aims to reduce bias at input level (user–item interactions) by learning a transformation from input space to a debiased subspace. As the output of this transformation lies in the same space as the original input vector, we can use transformed (debiased) input vectors without the need to fine-tune the pre-trained model. We evaluate the effectiveness of our method on three datasets, MovieLens-1M, LFM2b-DemoBias, and EB-NeRD, from the movie, music, and news domains, respectively. Our experiments show that the proposed method achieves task performance (in terms of NDCG) and debiasing strength (in terms of balanced accuracy of an attacker network) that are comparable to applying adversarial training during the initial training procedure, while providing the added functionality of alternating between biased and debiased model at inference time." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://dl.acm.org/doi/10.1145/3705328.3748012
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: userbias
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_recsys_maskmult_teaser.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_recsys_maskmult_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- penz
- escobedo-ticona
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: RECSYS
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  journal:  # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the Nineteenth ACM Conference on Recommender Systems
  editor: 
  publisher: ACM
  address: 
  doi: 10.1145/3705328.3748012
  url:  https://doi.org/10.1145/3705328.3748012
  volume: 
  number: 
  pages: 632 - 636
  month: September

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


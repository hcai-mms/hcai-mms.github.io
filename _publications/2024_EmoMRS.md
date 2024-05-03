---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Emotion-Based Music Recommendation from Quality Annotations and Large-Scale User-Generated Tags" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Emotions constitute an important aspect when listening to music. While manual annotations from user studies grounded in psychological research on music and emotions provide a well-defined and fine-grained description of the emotions evoked when listening to a music track, user-generated tags provide an alternative view stemming from large-scale data. In this work, we examine the relationship between these two emotional characterizations of music and analyze their impact on the performance of emotion-based music recommender systems individually and jointly. Our analysis shows that (i) the agreement between the two characterizations, as measured with Cohen's $\kappa$ coefficient and Kendall rank correlation, is often low, (ii) Leveraging the emotion profile based on the intensity of evoked emotions from high-quality annotations leads to performances that are stable across different recommendation algorithms; (iii) Simultaneously leveraging the emotion profiles based on high-quality and large-scale annotations allows to provide recommendations that are less exposed to the low accuracy that algorithms might reach when leveraging one type of data, only."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://dl.acm.org/doi/10.1145/3604915.3608838 # https://dl.acm.org/doi/abs/10.1145/3511808.3557656
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: emomrs
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2024_EmoMRS.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2024_EmoMRS.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- moscati
- Hannah Strauß
- Peer-Ole Jacobsen
- Andreas Peintner
- Eva Zangerle
- Marcel Zentner
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: UMAP
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 32nd ACM Conference on User Modeling,
Adaptation and Personalization (UMAP)
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  doi: 10.1145/3627043.3659540
  url:  
  volume: 
  number: 
  pages: 
  year: 2024
  month: 
  location: Cagliari, Italy

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
pdf: /assets/pdf/2024_umap_emomrs.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: /assets/pdf/2024_umap_emomrs_poster.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
code: https://github.com/hcai-mms/emo-mrs

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

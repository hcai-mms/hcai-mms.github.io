---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Extending Logic Tensor Networks to Implicit Feedback for Representation-Aware Music Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "msthesis": Master Thesis 
# "phdthesis": Phd. Thesis  
type: paper
abstract: "Music recommender systems shape how people discover music, yet persistent concerns have been raised regarding fairness and representation. Achieving fairness in recommender systems is challenging because conventional methods rely on rigid quantitative criteria, making it difficult to express nuanced or socially informed fairness goals. We explore the use of Logic Tensor Networks (LTNs) to incorporate nuanced fairness constraints into music recommender systems. LTNs enable the formulation of soft, differentiable constraints in a specific first-order logic, allowing fairness to be expressed through expert knowledge or data-driven insights.  We make two main contributions. First, we extend an existing LTN-based recommender framework to the implicit-feedback setting. Second, we propose a procedure that uses the extended framework to integrate data-informed fairness regularization into matrix factorization (MF)-based music recommendation. We demonstrate effectiveness of the proposed procedure with a case study on country-level representation bias in music recommendation, where content from hegemonic markets (e.g., the U.S.) is often overrepresented while local music is underexposed. Our analysis reveals that this imbalance disproportionately affects users with high local mainstreaminess (those who prefer music popular within their own country) and low global mainstreaminess (those who prefer less globally popular music). Using LTNs, we design targeted, data-informed fairness constraints and show that our approach allows to mitigate these disparities while maintaining competitive recommendation quality. " # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: LTN4ImplicitFeedback
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2026_ecir_LTNs4IF.jpg
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2026_ecir_LTNs4IF.jpg

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- eckert
- lesota
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ECIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2026

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: 
bib:
  journal: 		# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 		# e.g.10.1109/TVCG.2020.3012063
  url: 
  volume: 
  number: 
  pages: 
  month: 

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

# Acknowledgements

Write acknowledgements for contributors.

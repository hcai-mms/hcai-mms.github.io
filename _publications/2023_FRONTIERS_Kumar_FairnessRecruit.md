---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Fairness of Recommender Systems in the Recruitment Domain: An Analysis from Technical and Legal Perspectives" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Recommender systems (RSs) have become an integral part of the hiring process, be it via job advertisement ranking systems (job recommenders) for the potential employee or candidate ranking systems (candidate recommenders) for the employer. As seen in other domains, RSs are prone to harmful biases, unfair algorithmic behavior, and even discrimination in a legal sense. Some cases, such as salary equity in regards to gender (gender pay gap), stereotypical job perceptions along gendered lines, or biases toward other subgroups sharing specific characteristics in candidate recommenders, can have profound ethical and legal implications. In this survey, we discuss the current state of fairness research considering the fairness definitions (e.g., demographic parity and equal opportunity) used in recruitment-related RSs (RRSs). We investigate from a technical perspective the approaches to improve fairness, like synthetic data generation, adversarial training, protected subgroup distributional constraints, and post-hoc re-ranking. Thereafter, from a legal perspective, we contrast the fairness definitions and the effects of the aforementioned approaches with existing EU and US law requirements for employment and occupation, and second, we ascertain whether and to what extent EU and US law permits such approaches to improve fairness. We finally discuss the advances that RSs have made in terms of fairness in the recruitment domain, compare them with those made in other domains, and outline existing open challenges." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: 
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: FairRecruit
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
#image_large: 2022_icmr_emomtb_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- kumar
- grosz 
- rekab-saz
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: Front. 
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://www.frontiersin.org/articles/10.3389/fdata.2023.1245198
# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Frontiers in Big Data - Recommender Systems
  booktitle: #Proceedings of the 2022 ACM International Conference on Multimedia Retrieval (ICMR)
  editor: 
  publisher: Association for Computing Machinery 
  address: New York, NY, USA
  doi: 10.1145/3608481
  url: https://doi.org/10.3389/fdata.2023.1245198
  volume: 6
  number: 
  pages: 
  month:
  location: 

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
pdf: # 
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


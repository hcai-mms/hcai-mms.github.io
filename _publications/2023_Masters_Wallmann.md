---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Explainable Sequential Music Recommender Systems: Integrating Collaborative Filtering and Theories of Human Memory" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: thesis
abstract: " With the advent of online music platforms, users experience an ever increasing volume of available music offers. As a consequence, users may feel overwhelmed. Recommender systems direct the attention of users to a small subset of music tracks that most likely match the taste of the users.

This thesis focuses on sequential music recommendation and in particular on session-completion, i.e., the task of recommending the remainder of a session given the knowledge of its initial segment. Music listening sessions often include repeated tracks. Research shows that modeling such individual relistening behavior with models of the human memory may be promising. In particular, Adaptive Control of Thought Rational (ACT-R) outperforms some strong baselines in session-completion. However, since recommender systems relying on ACT-R only can not make use of information encoded in the listening history of other users, these are unable to recommend novel tracks to users. In contrast, the main approach to recommender systems, collaborative filtering (CF), bases recommendations on listening histories of other similar users rather than on individual relistening behavior. CF-based recommender systems may recommend novel items, but their recommendations often lack explainability. A combination of CF and ACT-R may lead to novel and explainable recommendations combining individual relistening and listening behavior of other users. However, no prior research combining CF and ACT-R exists. To close this research gap, this thesis proposes several hybrid algorithms that integrate CF with ACT-R.

We provide three major contributions to the current research in the recommender system domain. First, we develop several new algorithms that combine ACT-R with CF for the task of session-completion. Second, we provide an extensive analysis of the performance of these algorithms on the large LFM-2b dataset of Last.fm listening histories, in comparison with well-established baselines and state-of-the-art models for the task of music session-completion. Performance is measured in terms of accuracy and beyond-accuracy metrics such as novelty, diversity, and popularity miscalibration of recommendations. In particular, we empirically identify for each beyond-accuracy metric an algorithm that performs best for it. Third, we demonstrate how some of the proposed algorithms can be used to explain music recommendations. Since each component of the memory module of ACT-R is designed to model a different aspect of human memory, the recommendations provided by the proposed algorithms are explainable. Additionally, we show how the explanations can be beneficial for users, platform providers, and producers."
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
- Wallmann, Christian

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/urn/urn:nbn:at:at-ubl:1-68113

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





---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Hybrid Music Recommendation Approach for Heterogeneous Information Network using Factorization Machines" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: thesis
abstract: "With the growth and complexity of heterogeneous music information network, it becomes necessary to have a deep understanding of the interaction reasons to discover how the users choose their preferences in order to build more effective recommendation systems. Moreover, even when the recommendation model embeds user-item interactions, if we analyze the user preferences, we miss references to important content-based information or actual semantics of recommended items, which support the interpretation of a recommendation process. In this thesis, we will build a hybrid recommendation model based on content-based, context-based and collaborative filtering recommendation methods to leverage heterogeneous music information graph. To achieve this goal, a Music Information Knowledge Graph (MKG) is first constructed to encode different kinds of heterogeneous information, including the interactions between users, tracks and artists. Besides, we propose a hybrid music recommendation approach for MKG using factorization machines.

In the experimental part, we collect data from a wide and popular music platform called LastFM which contains a detailed profile of each user's musical taste and details of the tracks the user listens to. Moreover, we extend our dataset to be more effective by involving data about the content characteristic of the collected tracks (tracks content data) and the artists who sing these tracks (artists context data). Therefore, we get the content characteristic of the tracks from Spotify and we collect the artist details from DBpedia. Finally, all these data resources are integrated into MKG.

Building Hybrid recommender based on MKG and factorization machines techniques shows that dealing with relevant content and context information can be used to increase the recommendation accuracy and to improve the awareness of the reasons behind user's preferences." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

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
shortname: mastersthesis
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
- Majd Azzam

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2021

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: 

# what is the publication type and other bib specific properties
bibentry: misc
bib:
  journal: # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  editor: 
  publisher: 
  address: 
  doi: 	# e.g.10.1109/TVCG.2020.3012063
  url: "https://resolver.obvsg.at/urn:nbn:at:at-ubl:1-44265"
  volume: 
  number: 
  pages: 
  month:
  school: Johannes Kepler University Linz 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: https://resolver.obvsg.at/urn:nbn:at:at-ubl:1-44265
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






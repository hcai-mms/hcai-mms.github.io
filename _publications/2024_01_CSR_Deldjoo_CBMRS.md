---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Content-driven music recommendation: Evolution, state of the art, and challenges" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "The music domain is among the most important ones for adopting recommender systems technology. In contrast to most other recommendation domains, which predominantly rely on collaborative filtering (CF) techniques, music recommenders have traditionally embraced content-based (CB) approaches. In the past years, music recommendation models that leverage collaborative and content data – which we refer to as content-driven models – have been replacing pure CF or CB models. In this survey, we review 55 articles on content-driven music recommendation. Based on a thorough literature analysis, we first propose an onion model comprising five layers, each of which corresponds to a category of music content we identified: signal, embedded metadata, expert-generated content, user-generated content, and derivative content. We provide a detailed characterization of each category along several dimensions. Second, we identify six overarching challenges, according to which we organize our main discussion: increasing recommendation diversity and novelty, providing transparency and explanations, accomplishing context-awareness, recommending sequences of music, improving scalability and efficiency, and alleviating cold start. Each article addresses one or more of these challenges and is categorized according to the content layers of our onion model, the article’s goal(s), and main methodological choices. Furthermore, articles are discussed in temporal order to shed light on the evolution of content-driven music recommendation strategies. Finally, we provide our personal selection of the persisting grand challenges which are still waiting to be solved in future research endeavors." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: CSR_2024
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
# image_large: placeholder.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Deldjoo, Yashar
- schedl
- Knees, Peter 

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CSR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Computer Science Review # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  location: 
  doi: 10.1016/j.cosrev.2024.100618	# e.g.10.1109/TVCG.2020.3012063
  url: https://www.sciencedirect.com/science/article/pii/S1574013724000029
  volume: 51
  number: 12
  pages: 100618
  issn: 1574-0137
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
# code: https://github.com/hcai-mms/ProtoMF

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

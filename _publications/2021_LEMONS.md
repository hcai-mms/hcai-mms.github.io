---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "LEMONS: Listenable Explanations for Music recOmmeNder Systems" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Although current music recommender systems suggest new tracks to their users, they do not provide listenable explanations of why a user should listen to them. LEMONS (Demonstration video: https://youtu.be/giSPrPnZ7mc) is a new system that addresses this gap by (1) adopting a deep learning approach to generate audio content-based recommendations from the audio tracks and (2) providing listenable explanations based on the time-source segmentation of the recommended tracks using the recently proposed audioLIME." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: # https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: LEMONS
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2021_lemons.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2021_lemons_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- melchiorre
- Haunschmid, Verena 
- schedl
- Widmer, Gerhard 

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ECIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2021

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 43rd European Conference on Information Retrieval (ECIR)
  editor: "Hiemstra, Djoerd and Moens, Marie-Francine and Mothe, Josiane and Perego, Raffaele and Potthast, Martin and Sebastiani, Fabrizio"
  publisher: "Springer International Publishing"
  address: 
  doi: 10.1007/978-3-030-72240-1_60		# e.g.10.1109/TVCG.2020.3012063
  url: https://doi.org/10.1007/978-3-030-72240-1_60
  volume: 58
  number: 5
  pages: 531--536
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
youtube-id: giSPrPnZ7mc 
# the youtube-id of the preview-video
preview-youtube-id: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: /assets/pdf/2021_ecir_lemons.pdf
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
code: https://github.com/CPJKU/LEMONS

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
Lemons.md

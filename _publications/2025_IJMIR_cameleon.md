---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Chameleon: A Multimodal Learning Framework Robust to Missing Modalities" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Multimodal learning has demonstrated remarkable performance improvements over unimodal architectures. However, multimodal learning methods often exhibit deteriorated performances if one or more modalities are missing. This may be attributed to the commonly used multi-branch design containing modality-specific components, making such approaches reliant on the availability of a complete set of modalities. In this work, we propose a robust multimodal learning framework, Chameleon, that adapts a common-space visual learning network to align all input modalities. To enable this, we present the unification of input modalities into one format by encoding any non-visual modality into visual representations thus making it robust to missing modalities. Extensive experiments are performed on multimodal classification task using four textual-visual (Hateful Memes, UPMC Food-101, MM-IMDb, and Ferramenta) and two audio-visual (avMNIST, VoxCeleb) datasets. Chameleon not only achieves superior performance when all modalities are present at train/test time but also demonstrates notable resilience in the case of missing modalities." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://link.springer.com/article/10.1007/s13735-025-00370-y
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: Chameleon
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_chameleon.png
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
- liaqat
- nawaz
- Zaheer, Muhammad Zaigham 
- Saeed, Muhammad Saad 
- Sajjad, Hassan 
- De Schepper, Tom 
- Nandakumar, Karthik 
- Khan, Muhammad Haris 
- Gallo, Ignazio 
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: IJMIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: International Journal of Multimedia Information Retrieval # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 10.1007/s13735-025-00370-y	
  url: https://doi.org/10.1007/s13735-025-00370-y
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

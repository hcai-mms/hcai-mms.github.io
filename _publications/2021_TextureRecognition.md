---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Automatic Recognition of Texture in Renaissance Music" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Renaissance music constitutes a resource of immense richness for Western culture, as shown by its central role in digital humanities. Yet, despite the advance of computational musicology in analysing other Western repertoires, the use of computer-based methods to automatically retrieve relevant information from Renaissance music, e. g.,identifying word-painting strategies such as madrigalisms, is still underdeveloped. To this end, we propose a scorebased machine learning approach for the classification of texture in Italian madrigals of the 16th century. Our outcomes indicate that Low Level Descriptors, such as intervals, can successfully convey differences in High Level features, such as texture. Furthermore, our baseline results, particularly the ones from a Convolutional Neural Network, show that machine learning can be successfully used to automatically identify sections in madrigals associated with specific textures from symbolic sources." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://archives.ismir.net/ismir2021/paper/000063.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: TextureRecognition
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2021_ismir_musictexture.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2021_ismir_musictexture_teaser_C.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- parada-cabaleiro
- Maximilian Schmitt
- Anton Batliner
- Björn Schuller
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ISMIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2021

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://archives.ismir.net/ismir2021/paper/000063.pdf # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: International Society for Music Information Retrieval # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  editor: 
  publisher: 
  address: 
  doi:		# e.g.10.1109/TVCG.2020.3012063
  url: https://archives.ismir.net/ismir2021/paper/000063.pdf 
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
code: https://github.com/SEILSdataset/Texture_Recognition

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---





---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Perception and classification of emotions in nonsense speech: Humans versus machines" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "This article contributes to a more adequate modelling of emotions encoded in speech, by addressing four fallacies prevalent in traditional affective computing: First, studies concentrate on few emotions and disregard all other ones (‘closed world’). Second, studies use clean (lab) data or real-life ones but do not compare clean and noisy data in a comparable setting (‘clean world’). Third, machine learning approaches need large amounts of data; however, their performance has not yet been assessed by systematically comparing different approaches and different sizes of databases (‘small world’). Fourth, although human annotations of emotion constitute the basis for automatic classification, human perception and machine classification have not yet been compared on a strict basis (‘one world’). Finally, we deal with the intrinsic ambiguities of emotions by interpreting the confusions between categories (‘fuzzy world’). We use acted nonsense speech from the GEMEP corpus, emotional ‘distractors’ as categories not entailed in the test set, real-life noises that mask the clear recordings, and different sizes of the training set for machine learning. We show that machine learning based on state-of-the-art feature representations (Wav2vec2) is able to mirror the main emotional categories (‘pillars’) present in perceptual emotional constellations even in degradated acoustic conditions." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: 
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: HumanVSMachine
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_plos1_humanvsmachine_teaser.eps
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2023_plos1_humanvsmachine.eps

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- parada-cabaleiro
- Batliner, Anton
- Schmitt, Maximilian
- schedl
- Costantini, Giovanni
- Schuller, Björn

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: PLOS ONE
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: 

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: PLOS ONE To Appear
  booktitle: #
  editor: 
  publisher: 
  address: 
  doi: 
  url: 
  volume:
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
# - name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: 

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


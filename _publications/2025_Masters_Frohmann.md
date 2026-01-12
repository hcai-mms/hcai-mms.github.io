---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Robust AI-Generated Lyrics Detection" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: thesis
abstract: "The rapid advance of Artificial Intelligence (AI)-based music genera-tion tools presents new opportunities for the music industry but alsoposes significant challenges, necessitating reliable methods for detect-ing AI-generated content. Existing detectors, however, face key practi-cal limitations: audio-based approaches struggle to generalize to un-seen generators and are not robust to common audio perturbations,while lyrics-based methods depend on cleanly formatted lyrics that areunavailable in real-world settings. To address this gap, this thesis pro-poses and evaluates a novel, practically grounded approach that lever-ages lyrical content extracted directly from the audio signal. Our methodfirst transcribes sung lyrics using a general-purpose Automatic SpeechRecognition (ASR) model, allowing established AI-generated text de-tection methods to be applied. To further improve performance, we in-troduce Double Entendre-detect (DE-detect), a multi-view late-fusionmethod that also incorporates audio-derived speech features capturingparalinguistic information. By focusing on lyrical and speech-relatedinformation rather than low-level audio artifacts, our method is de-signed for improved robustness and generalization. Experiments on adiverse dataset show that DE-detect achieves strong detection perfor-mance compared to text-only ones and, crucially, outperforms audio-based approaches, especially when tested against various audio pertur-bations and unseen music generators. This work thus presents an effec-tive, robust, and practical solution for detecting AI-generated music."
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
- Markus Frohmann 

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/download/pdf/13104267.pdf 
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





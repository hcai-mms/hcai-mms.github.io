---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Frame-to-Utterance Convergence: A Spectra-Temporal Approach for Unified Spoofing Detection" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Voice spoofing attacks pose a significant threat to automated speaker verification systems. Existing anti-spoofing methods often simulate specific attack types, such as synthetic or replay attacks. However, in real-world scenarios, the countermeasures are unaware of the generation schema of the attack, necessitating a unified solution. Current unified solutions struggle to detect spoofing artefacts, especially with recent spoofing mechanisms. For instance, the spoofing algorithms inject spectral or temporal anomalies, which are challenging to identify. To this end, we present a spectra-temporal fusion leveraging frame-level and utterance-level coefficients. We introduce a novel local spectral deviation coefficient (SDC) for frame-level inconsistencies and employ a bi-LSTM-based network for sequential temporal coefficients (STC), which capture utterance-level artifacts. Our spectra-temporal fusion strategy combines these coefficients, and an auto-encoder generates spectra-temporal deviated coefficients (STDC) to enhance robustness. Our proposed approach addresses multiple spoofing categories, including synthetic, replay, and partial deepfake attacks. Extensive evaluation on diverse datasets (ASVspoof2019, ASVspoof2021, VSDC, partial spoofs, and in-the-wild deepfakes) demonstrated its robustness for a wide range of voice applications."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://dl.acm.org/doi/10.1145/3604915.3608838 # https://dl.acm.org/doi/abs/10.1145/3511808.3557656
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: frame
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: placeholder.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Khan, Awais
- Malik, Khalid Mahmood
- nawaz

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ICASSP
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
key: khan2024frame
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: ICASSP 2024-2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)
  editor: 
  publisher:
  address: 
  doi:  10.1109/ICASSP48485.2024.10447500
  url:  
  volume: 
  number: 
  pages: 10761--10765
  month: 
  location: 

preprint:	https://arxiv.org/abs/2309.09837 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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
# pdf: /assets/pdf/2024_recsys_sibrar.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
# supplement: /assets/pdf/2024_recsys_supplementar.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
github:

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "SwapRec: Warming Up Cold Items Through Training-Time Similar-Content Swaps" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Interactions with cold items negatively impact real-time personalization of ID-based recommender systems. This is because the use of such interactions degrades user preference estimates, whereas excluding cold items from the user profile prevents real-time recommendation updates. In industrial scenarios, one heuristic often applied to address this shortcoming at inference time is to replace, i. e., “swap”, cold-start items by their most similar “warm” neighbor, where similarity is inferred from the items’ side information. In this paper, we demonstrate that sequential models, most often used for real-time personalization, are not robust to such swaps, and propose SwapRec , an approach to address this issue. SwapRec relies on using the same swap heuristics already at training time. We apply SwapRec to state-of-the-art models for sequential recommendation and analyze its impact by means of quantitative experiments in three recommendation domains (online shopping, movie, music). The experimental results show that, irrespective of the underlying sequential architecture, our easy-to-implement SwapRec approach allows for substantially more accurate recommendations when in presence of interactions with cold items, simultaneously leading to a larger percentage of cold items in the recommendation lists." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: 
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: SwapRec
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: SwapRec.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: SwapRec.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- moscati
- Jan Malte	Lichtenberg
- Davide	Abbattista
- Antonio	De Candia
- Laura	Boggia
- Matteo Ruffini

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CEUR Workshop Proceedings
# when was this publication written/ when was the publication accepted (e.g. 2020)
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2026

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://ceur-ws.org/Vol-4188/ # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  booktitle: Proceedings of DaQuaMRec 2026, the 2nd International Workshop on Data Quality-Aware Multimodal Recommendation, co-located with the 20th ACM Conference on Recommender Systems (RecSys 2026), September 28 - October 2, 2026, Minneapolis, Minnesota, USA.
  editor: 
#  publisher: Association for Computing Machinery
#  address: New York, NY, USA
#  doi: 10.1145/3705328.3759302
#  url: https://doi.org/10.1145/3705328.3759302
#  volume: 
#  number: 
#  pages: 1256–1260

# preprint:	https://arxiv.org/abs/2601.13651 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
# award:

# state key of an internal tool. This will link to the tool site e.g. lineup (usually not needed)
# project: 

# Use this if you have an external project website e.g. https://ordino.caleydoapp.org/
# external-project: 

# (deprecated)
# # The key of the video .md file (in _videos subfolder)
# video: 
# # The key of the preview video .md file (in _videos subfolder)
# preview-video:

# the youtube-id of the video
# youtube-id:
# the youtube-id of the preview-video
# preview-youtube-id: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
# pdf: /assets/pdf/2026_ICASSP_MSM.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
# supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
# code: https://github.com/hcai-mms/MSM-face-voice

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


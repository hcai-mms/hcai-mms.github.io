---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Large Language Models for Intent-aware Music Recommendation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: msthesis
abstract: "Intent-aware music recommender systems are relatively new and advanced approaches in personalized music recommendation. By the integration of the user’s current intent - their main aim for the consumption of the content - these recommender systems can provide more meaningful suggestions that improve user satisfaction. At the same time, Large Language Models (LLMs) appear in many applications nowadays, so it is no surprise that they can have a significant potential and can unlock new opportunities for recommender systems too. Thus, combining these two fields - namely LLMs and intent-aware music recommendation – offers opportunities to improve personalized music recommendations. This thesis investigates the potential of LLMs for intent-aware music recommendation by studying how listening intents can be included in LLM prompts to improve the relevance and intent-alignment of recommendations. 2 main research questions guide this work: (i) How does the inclusion of listening intent and user preferences in LLM prompts affect the relevance and intent-alignment of music recommendations? and (ii) What is the impact of different track–intent assignment strategies on recommendation quality of intent-aware music recommenders using LLMs? To address these questions, an LLM-based intent-aware music recommender framework is developed that combines the 2020 subset of the LFM-2b dataset, which includes user–track interactions, with the Spotify Million Playlist Dataset enriched with listening intent annotations for each playlist, based on which 5 distinct track-intent matching approaches are implemented to define listening intents on the track level too. 2 LLMs (Google’s Gemini 1.5 Flash and Mistral 7B Instruct v0.3) are evaluated against a Factorization Machine baseline capable of integrating contextual features such as the listening intent of the user. Recommendations are offline evaluated using fuzzy string matching between recommended songs and ground-truth user history tracks in 3 ways: (i) content relevance, where the recommended track has to match one of the tracks the user previously listened to, regardless of the listening intent, (ii) intent-aware relevance, where the listening intent also needs to match, and (iii) intent calibration, which measures distributional alignment between listening intents in the user’s history data and in the recommended songs. Standard accuracy-based and beyond-accuracy metrics such as precision, recall, F1 score, NDCG, MRR, coverage, artist diversity, and hit rate at 10 are also utilized to assess the recommended songs. The results show that including listening intents into LLM prompts improves recommendation quality and intent alignment relative to intent-agnostic prompting strategies, while the Factorization Machine model still provides a competitive baseline. However, several limitations emerge due to the restricted offline evaluation setting, the reliance on fuzzy string matching, and due to the vulnerability of track-intent matching approaches to the robustness of playlist-intent mappings. Additionally, the LLM-based intent-aware music recommender framework faces some scalability challenges, as the need to query an LLM for every user–intent pair introduces computational bottlenecks that can limit feasibility for large-scale deployment.Overall, this thesis provides insights into the integration of LLMs to the field of intentaware music recommendation, and highlights both their potential and their current limitations for large-scale, real-world deployment."
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
- Petra Jósár

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/obvulihs/content/titleinfo/12791432
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





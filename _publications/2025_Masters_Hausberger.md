---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Generating Contextbased Music Playlists for Mood Regulation: An Approach Based on Contrastive Learning" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: thesis
abstract: "The influence of music on human emotions and behavior has been recognized for a long time, with applications spanning therapeutic interventions and veryday mood regulation. This Master thesis explores the potential of music to modulate emotional states in real-world settings by developing a context-aware system for playlist generation aimed at enhancing specific mood parameters. This study employs a two-stage approach to model training. First, a representation model is pre-trained to learn multimodal music representations by capturing similarities across various modalities, including Mel spectrograms, genre, tags, emotional tags, and lyrics. This pre-training enables the model to learn to represent a music track in multiple ways over multiple modalities, finding representations that maximize the mutual information between the Mel spectrogam and another modality. Subsequently, a mood context representation model is fine-tuned to align music track representations with the contextual features of listening sessions. Leveraging these learned representations, the system predicts the emotional and contextual suitability of tracks and their impact on mood, thereby facilitating the creation of playlists tailored to evoke specific emotional effects and suit diverse situational contexts. This Master thesis systematically evaluates the proposed models and compares them against state-of-the-art representation models. While the proposed model does not exhibit superior generalization across multiple benchmark datasets, it demonstrates improved similarity between representations of tracks grouped by emotional tags and emotional numeric information. To assess the system’s effectiveness, two user studies were conducted. The first study collected music listening sessions and contextual information to enhance model training, while the second examined user perceptions of the generated playlists concerning mood regulation and contextual relevance. The findings underscore the inherent subjectivity of music perception, as the same playlist elicited varied responses among different users. The studies further emphasize the importance of user preferences, revealing that ratings fluctuate based on context and are highly individualized. This Master thesis contributes to the field of music recommendation by demonstrating the feasibility of integrating contextual and emotional data into automatic playlist generation. Additionally, it provides insights into the strengths and limitations of current representation models and the role of user preferences in music suitability for certain contexts."
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
- parada-cabaleiro
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
- hausberger

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/download/pdf/11796443.pdf
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





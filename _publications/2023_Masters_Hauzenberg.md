---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Modular DiffPruning for Bias Mitigation" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: thesis
abstract: "In recent years, large language models have achieved state of the art performance on a wide variety of Natural Language Processing tasks. These capabilities however come with some negative consequences, namely the existence of various societal biases in these models. Furthermore due to their size, storage and inference are becoming increasingly challenging and often require industry-grade infrastructure. In this research, we present a novel solution to address both of these challenges. We build upon two established approaches: first, adversarial training, a common (in-processing) bias mitigation approach which encourages a model to update its parameters during training such that the model can perform a task in an debiased way. Second, Diff pruning which enables storing finetuned models in a parameter-efficient way. We combine both approaches and propose a novel modular bias mitigation technique, where information for debiasing a protected attribute is learned and stored in a sparse subnetwork, which can be added to a pre-trained model on-demand. We show the effectiveness of our method based on a large set of experiments for three protected attributes (gender, age, and race dialect), and on three datasets. The results show that our modular approach has several benefits: it leads to significant reduction in bias while maintaining task performance compared to several strong baselines, it is parameter-efficient, allows for the creation of modular bias mitigation Diff masks, and enables the integration of these bias mitigation modules as needed."
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
- rekab-saz


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
- Hauzenberger, Lukas 

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/urn/urn:nbn:at:at-ubl:1-58968

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





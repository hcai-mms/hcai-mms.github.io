---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "The Effect of Coresets on Demographic Bias in Encoder-Only Transformer Models for Text Classification" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: msthesis
abstract: "This thesis evaluates whether coreset-based data selection (where a coreset is a subset of the original training set) can reduce demographic performance gaps in encoder-only transformer text classifiers without substantially reducing balanced accuracy. We compare four selection strategies (Active Learning (AL), K-Center Greedy (KCG), K-Means, and a Hybrid strategy combining KCG and AL) using a fixed coreset size of 25% across five encoder-only transformer backbones on three classification datasets (PAN16, FDCL18, and BIOS). Each strategy is evaluated against the corresponding full-training-set baseline classifier for each backbone. We quantify demographic disparity using balanced-accuracy gaps between groups under predefined demographic train–test scenarios, and we report overall balanced accuracy alongside these gap metrics. The results show that coreset selection can meaningfully change demographic disparities, but the direction and magnitude of the effect vary across datasets and demographic variables. Overall, KCG and Hybrid emerge most consistently as strong accuracy–fairness trade-offs, though no single strategy dominates across all datasets. These findings suggest that coreset selection can be a useful data-centric intervention in this setting, while highlighting limits to generalization beyond the tasks and metrics evaluated here."
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
- kumar


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
- Mahmoud Mohammad Aref Barham

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2026

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: # https://epub.jku.at/download/pdf/13308557.pdf
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





---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Measuring Gender Bias in Information Retrieval Models" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: thesis
abstract: "Information Retrieval (IR) is crucial for finding digital information, and search engines based on IR form an integral part of our daily lives. However, these systems can reinforce harmful societal biases, including gender bias, contributing to a vicious cycle of bias between data, algorithm, and user. Therefore, it is essential to define reliable metrics for quantifying gender bias in IR systems and to understand the reinforcing mechanisms in the ecosystem.
In this thesis, we propose a novel extrinsic (application level) metric that measures bias in search results, a semi-extrinsic metric that assesses the bias in rankings of selected documents, and an intrinsic metric that evaluates the bias in query embeddings. We compare two types of extrinsic metrics: metrics based on the occurrence of gender-specific language in the search results and metrics that define bias as a skew in the search results of a non-gendered query toward those for gender-specific variations of the same query. Conducting experiments on a set of non-gendered bias-sensitive queries, we find that the former only perform well in certain subject areas while the latter are more susceptible to the influence of irrelevant search results. We further investigate the correlation of the bias measurements of the three metrics. Our experiments indicate a moderate positive correlation between the intrinsic and extrinsic metric results across three analysed IR models. They indicate a high positive correlation between the semi-extrinsic and extrinsic metric results across five IR models, whereby the per-model results for two of the five models show a negative or no correlation. We further use the metrics to measure bias in models before and after fine-tuning them using biased user interaction data. We find that 10 out of 13 bias measurements across different models indicate an increase in bias. However, only the semi-extrinsic metric detects a significant effect. Overall, our work contributes to the advancement of reliable metrics for measuring bias in IR."
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
- Ratz, Linda 

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/urn/urn:nbn:at:at-ubl:1-62438

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





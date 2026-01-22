---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "In-Task Knowledge Transfer: Applying AdapterFusion to Dense Passage Retrieval" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: msthesis
abstract: "Pre-training and fine-tuning methods have greatly advanced information retrieval (IR). Tra- ditionally, all parameters of extensive pre-trained language models were fine-tuned for specific tasks. However, the growing size of these models and the multitude of tasks have made this approach less practical and more resource-intensive. In recent natural language processing (NLP) developments, there is a growing interest in methods for fine-tuning fewer parameters while still maintaining good or on-par performance. These approaches are typically called parameter-efficient fine-tuning methods. On top of one of these well-proven methods called Adapters, a knowledge transfer method called AdapterFusion was introduced. This allows in a two-stage manner to combine knowledge without the risk of catastrophic forgetting. Various works have used this method to realize modern approaches to bias mitigation, cross-lingual NLP tasks and more. All these applications have in common that they combine knowledge from two separate tasks. In this work, we want to apply AdapterFusion within the same task of IR to see if we can improve the performance of dense passage retrieval (DPR). We run vari- ous experiments with Adapters and AdapterFusion on the MSMARCO passage retrieval task dataset to investigate this topic. By replacing the fully fine-tuned encoder in a DPR setup with a parameter-efficient Adapter-based encoder we show that in a single encoder retriever setup, this does not come with a cost in performance. With only 0.597% of trainable pa- rameters, in comparison to the fully fine-tuned encoder, we not only achieve to maintain the same retrieval performance but also create substantially smaller model checkpoints. Further, by training specific Adapters for query encoding and passage encoding in each a parallel and isolated training setup, we discover that the learning capability of the query encoder is higher in the isolated setup. By then combining these Adapters in various AdapterFusion models we show that we can achieve a successful in-task knowledge transfer that allows the Fusion models to perform better than the individual query and passage Adapters. We compare the results to the single Adapter baseline and the fully fine-tuned baseline and cannot find any significant improvement after the in-task knowledge transfer. Additionally, we analyze the Adapter activations in the AdapterFusion layers and see that even though the passage Adapters are mostly activated the strongest in all systems, we cannot achieve a solid result without a well-trained query Adapter."
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
- Obermann, David 

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/urn/urn:nbn:at:at-ubl:1-71505

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





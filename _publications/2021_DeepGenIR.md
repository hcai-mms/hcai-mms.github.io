---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "A Modern Perspective on Query Likelihood with Deep Generative Retrieval Models" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Existing neural ranking models follow the text matching paradigm, where document-to-query relevance is estimated through predicting the matching score. Drawing from the rich literature of classical generative retrieval models, we introduce and formalize the paradigm of deep generative retrieval models defined via the cumulative probabilities of generating query terms. This paradigm offers a grounded probabilistic view on relevance estimation while still enabling the use of modern neural architectures. In contrast to the matching paradigm, the probabilistic nature of generative rankers readily offers a fine-grained measure of uncertainty. We adopt several current neural generative models in our framework and introduce a novel generative ranker T-PGN, which combines the encoding capacity of Transformers with the Pointer Generator Network model. We conduct an extensive set of evaluation experiments on passage retrieval, leveraging the MS MARCO Passage Re-ranking and TREC Deep Learning 2019 Passage Re-ranking collections. Our results show the significantly higher performance of the T-PGN model when compared with other generative models. Lastly, we demonstrate that exploiting the uncertainty information of deep generative rankers opens new perspectives to query/collection understanding, and significantly improves the cut-off prediction task." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://dl.acm.org/doi/pdf/10.1145/3471158.3472229
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: DeepGenIR
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2021_deepgenir.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2021_deepgenir_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- lesota
- rekab-saz
- Cohen, Daniel 
- Grasserbauer, Klaus Antonius 
- Eickhoff, Carsten 
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ICTIR
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2021

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://dl.acm.org/doi/10.1145/3471158.3472229 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Proceedings of the 2021 ACM SIGIR International Conference on Theory of Information Retrieval # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  editor: 
  publisher:
  address: 
  doi:	10.1145/3471158.3472229	# e.g.10.1109/TVCG.2020.3012063
  url: 
  volume: 
  number: 
  pages: 185--195
  month: July

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
code: https://github.com/CPJKU/DeepGenIR

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgments

This research is supported in part by the NSF (IIS-1956221). The views and conclusions contained herein are those of the authors and should not be interpreted as necessarily representing the official policies, either expressed or implied, of NSF or the U.S. Government. This research is also supported by Know-Center Graz, through project “Theory-inspired Recommender Systems”.
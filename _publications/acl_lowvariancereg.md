---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing, pages 10932–10938 November 12-16, 2024 ©2024 Association for Computational LinguisticsUnlabeled Debiasing in Downstream Tasks via Class-wise Low Variance Regularization" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Language models frequently inherit societalbiases from their training data. Numerous tech-niques have been proposed to mitigate thesebiases during both the pre-training and fine-tuning stages. However, fine-tuning a pre-trained debiased language model on a down-stream task can reintroduce biases into themodel. Additionally, existing debiasing meth-ods for downstream tasks either (i) require la-bels of protected attributes (e.g., age, race, orpolitical views) that are often not available or(ii) rely on indicators of bias, which restrictstheir applicability to gender debiasing sincethey rely on gender-specific words. To addressthis, we introduce a novel debiasing regulariza-tion technique based on the class-wise varianceof embeddings. Crucially, our method doesnot require attribute labels and targets any at-tribute, thus addressing the shortcomings ofexisting debiasing methods. Our experimentson encoder language models and three datasetsdemonstrate that our method outperforms ex-isting strong debiasing baselines that rely ontarget attribute labels while maintaining perfor-mance on the target task."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://aclanthology.org/2024.emnlp-main.612.pdf # https://aclanthology.org/2024.emnlp-main.612.pdf
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: acl_lowvariancereg
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
- masoudian
- Markus Frohmann
- Navid Rekabsaz
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ACM
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: masoudian-etal-2024-unlabeled
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing (ACM)
  editor: Yaser Al-Onaizan, Mohit Bansal, Yun-Nung Chen
  publisher: Association for Computing Machinery
  address: Miami, Florida, USA
  doi: 10.18653/v1/2024.emnlp-main.612
  url:  https://aclanthology.org/2024.emnlp-main/
  volume: 
  number: 
  pages: 10932-10938
  month: November
  location: 

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
code: 

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

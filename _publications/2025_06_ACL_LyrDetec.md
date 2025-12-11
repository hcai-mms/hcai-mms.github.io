---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "BreastCare application: Moroccan Breast cancer diagnosis through deep learning-based image segmentation and classification" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Breast cancer remains a critical health problem worldwide. Increasing survival rates requires early detection. Accurate classification and segmentation are crucial for effective diagnosis and treatment. Although breast imaging modalities offer many advantages for the diagnosis of breast cancer, the interpretation of breast ultrasound images has always been a vital issue for physicians and radiologists due to misdiagnosis. Moreover, detecting cancer at an early stage increases the chances of survival. This article presents two approaches: Attention-DenseUNet for the segmentation task and EfficientNetB7 for the classification task using public datasets: BUSI, UDIAT, BUSC, BUSIS, and STUHospital. These models are proposed in the context of Computer-Aided Diagnosis (CAD) for breast cancer detection. In the first study, we obtained an impressive Dice coefficient for all datasets, with scores of 88.93%, 95.35%, 92.79%, 93.29%, and 94.24%, respectively. In the classification task, we achieved a high accuracy using only four public datasets that include the two classes benign and malignant: BUSI, UDIAT, BUSC, and BUSIS, with an accuracy of 97%, 100%, 99%, and 94%, respectively. Generally, the results show that our proposed methods are considerably better than other state-of-the-art methods, which will undoubtedly help improve cancer diagnosis and reduce the number of false positives. Finally, we used the suggested approaches to create “Moroccan BreastCare”, an advanced breast cancer segmentation and classification software that automatically processes, segments, and classifies breast ultrasound images." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://doi.org/10.1016/j.ibmed.2025.100254
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: Breastcare
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_breastcancer.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_breastcancer.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - schedl # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Nouhaila Erragzi
- Nabila Zrira
- Safae Lanjeri
- Youssef Omor
- Anwar Jimi
- Ibtissam Benmiloud
- Rajaa Sebihi
- Rachida Latib
- Nabil Ngote
- Haris Ahmad Khan
- nawaz

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: 
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: IEEE International Conference on Content-Based Multimedia Indexing # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: "Intelligence-Based Medicine"
  editor: 
  publisher: 
  address: 
  doi: 
  url: 
  volume: 
  number: 
  pages: 
  month: 

preprint:	https://doi.org/10.1016/j.ibmed.2025.100254 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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
- name: 
#  # use link instead of abslink if you want to link to the master directory
  abslink: 
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: 

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

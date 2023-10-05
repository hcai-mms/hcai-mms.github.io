---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Identifying Words in Job Advertisements Responsible for Gender Bias in Candidate Ranking Systems via Counterfactual Learning" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Candidate ranking systems (CRSs) for vacancies can pose a significant risk in terms of ethical considerations if they are prone to gender bias or even have legal implications if discriminatory behavior is found. In the case of content-based CRSs, which identify suited candidates for a given job opening based on their resumes and the job advert, gender bias in these texts can also lead to discriminatory behavior of the CRS algorithm. We propose an algorithm to automatically identify gendered words in the job advertisement responsible for gender bias in the rankings. The algorithm determines the words with gendered connotations in the rank distribution for a given job advertisement using content-based job-candidate matching based on the actual biography of a candidate and a counterfactual version in which explicit gender-mentioning terms are swapped between male and female. To this end, we employ the neural network explainability method of integrated gradients to compute CRS’s association of the job advertisement words with the gender of candidates, which we call the bias score of words. At the core of our CRS is a cross-encoder architecture. To showcase and validate our approach, we conduct a study investigating the gendered words identified by the proposed algorithm in job advertisements from a private dataset and biographies from the BIOS dataset. We analyze the gendered words along multiple job categories and different linguistic categories. Finally, we statistically and qualitatively compare them with standardized lists manually created by social psychologists to contrast the gender associations CRSs make with human associations." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: 
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: Red_Words_RecSysHR
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: placeholder.png
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
- kumar
- grosz
- Greif, Elisabeth
- rekab-saz
- schedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: CEUR Workshop Proceedings
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://ceur-ws.org/Vol-3490/RecSysHR2023-paper_7.pdf # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the 3rd Workshop on Recommender Systems for Human Resources (RecSys in HR 2023) co-located with the 17th ACM Conference on Recommender Systems (RecSys 2023) 
  editor: Kaya, Mesut and Bogers, Toine and Graus, David and Johnson, Chris and Decorte, Jens-Joris
  publisher: CEUR-WS.org
  address: 
  doi:		
  url: https://ceur-ws.org/Vol-3490/RecSysHR2023-paper_7.pdf
  volume: 3490
  number: 
  pages: 
  month: September

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
#  # use link instead of abslink if you want to link to the master directory
  # defaults to a download icon, use this if you want a link-out icon
  
# Link to the repository where the code is hostet
code: 

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

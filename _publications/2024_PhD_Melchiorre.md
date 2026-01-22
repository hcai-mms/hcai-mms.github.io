---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Explainable and Fair Music Recommender Systems" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: phdthesis
abstract: "Music Recommender Systems (MRS) are essential components of online music platforms, offering users personalized music recommendations from vast catalogs. Despite their convenience, there is growing concern over the fairness and explainability of these systems, as they may inadvertently reinforce biases, limit exposure to diverse content, and operate as 'black boxes' where the decision-making processes are opaque to users. Studies suggest that Recommender Systems' recommendation quality, including MRS', may vary based on user characteristics such as gender, age, or country of origin, potentially limiting access to quality content and reinforcing demographic-specific filter bubbles. Besides fairness, explaining why certain music items are recommended is important for maintaining user trust and supporting engineers in debugging the recommendation process. Explainability and fairness are noticeably intertwined, as explanations can aid in identifying potential biases and injustices within the systems, although transparent explanations alone do not ensure fair or biased results. This thesis provides several substantial contributions to the research directions of fairness and explainability in Recommender Systems in the music domain. Part I is devoted to assessing the disparate effectiveness of popular recommendation algorithms trained on large music datasets across different user groups. Focusing on the users' gender and personality, we uncover and measure the unfairness of most of the algorithms, demonstrating that they provide different quality of service to different user groups based on these characteristics. In Part II, we explore the role and methods of explainability in MRS by drawing connections to explainable AI and RSs, and we propose two novel explanation methods: ProtoMF, which uses prototypical users and items, as well as their similarities to real users and items, to explain recommendations, and LEMONS, which pinpoints the most meaningful part of the audio for track recommendations. Lastly, in Part III we jointly consider fairness and explainability in prototype-based RS models, proposing a debiasing method to make recommendation predictions less influenced by users' protected attributes like age and gender, effectively debiasing the RSs."
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
- Tommaso Di Noia


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: phd-thesis
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
- melchiorre 

# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://epub.jku.at/urn/urn:nbn:at:at-ubl:1-81098

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





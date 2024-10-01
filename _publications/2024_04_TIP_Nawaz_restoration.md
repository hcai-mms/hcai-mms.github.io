---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Single Stage Adaptive Multi-Attention Network for Image Restoration" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: journal
abstract: "Recently attention-based networks have been successful for image restoration tasks. However, existing methods are either computationally expensive or have limited receptive fields, adding constraints to the model. They are also less resilient in spatial and contextual aspects and lack pixel-to-pixel correspondence, which may degrade feature representations. In this paper, we propose a novel and computationally efficient architecture Single Stage Adaptive Multi-Attention Network (SSAMAN) for image restoration tasks, particularly for image denoising and image deblurring. SSAMAN efficiently addresses computational challenges and expands receptive fields, enhancing robustness in spatial and contextual feature representation. Its Adaptive Multi-Attention Module (AMAM), which consists of Adaptive Pixel Attention Branch (APAB) and an Adaptive Channel Attention Branch (ACAB), uniquely integrates channel and pixel-wise dimensions, significantly improving sensitivity to edges, shapes, and textures. We perform extensive experiments and ablation studies to validate the performance of SSAMAN. Our model shows state-of-the-art results on various benchmarks, for example, on image denoising tasks, SSAMAN achieves a notable 40.08 dB PSNR on SIDD dataset, outperforming Restormer by 0.06 dB PSNR, with 41.02% less computational cost, and achieves a 40.05 dB PSNR on the DND dataset. For image deblurring, SSAMAN achieves 33.53 dB PSNR on GoPro dataset. Code and models are available at Github."
####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url: https://dl.acm.org/doi/10.1145/3604915.3608838 # https://dl.acm.org/doi/abs/10.1145/3511808.3557656
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: restoration
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
- Zafar, Anas 
- Aftab, Danyal 
- Qureshi, Rizwan 
- Fan, Xinqi 
- Chen, Pingjun 
- Wu, Jia 
- Ali, Hazrat 
- nawaz
- Khan, Sheheryar 
- Shah, Mubarak


# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: TIP
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: https://link.springer.com/chapter/10.1007/978-3-030-72240-1_60 # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: inproceedings
key: zafar2024single
bib:
  # journal: Springer # e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: IEEE Transactions on Image Processing
  editor: 
  publisher:
  address: 
  doi:  10.1109/TIP.2024.3384838
  url:  
  volume: 33
  number: 
  pages: 2924 - 2935
  month: 
  location: 

preprint:	# here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969

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
github:

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

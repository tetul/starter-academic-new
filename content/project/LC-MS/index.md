---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "LC-MS of Neurochemicals"
summary: "I will be establishing the liquid chromatography- mass spectrometry method of quantifying neurochemicals from insect brains at the University of Konstanz. I will be using the Waters XEVO-TQS triple quadrupole mass spectrometer coupled to a Waters Acquity UPLC system.



This method is intended to be transferable to different insects. Current sub-projects include optimizing lyophilization conditions for brain dissections of ants, using in-house made stage-tips for sample cleanup and standardizing the Bradford method of protein estimation for species with large brain size variation."
authors: []
tags: []
categories: []
date: 2020-12-15

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Sequence of steps in the MS analysis"
  focal_point: "Top"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### Biological samples (sham ones)
Three ant brains, three honey bee and three bumble bee brains will be used to extract transmitters. Internal standards will be added to both the samples and the standards. The hope is for high dynamic range, and low matrix effect.  

### SPE and stage-tips
Empore doesn't make their teflon SPE disks anymore. So we bought ENVI disks. THese are glass fiber meshes with C-18 material in them. More difficult to punch out using the flat bore needle. How many disks, how much pressure to use to stack them? What is the loading capacity, recovery, and elution volume? On a whole, a mess. Loading capacitites with even 3 disks are low. Throughput is low because every tip has to be handled separately. Fast eluting compounds do not bind to the tips at all. The final decision is to proceed without the disks, unless the matrix effect is too high to ignore. 


### LC gradient
Converted a 35 min gradient to a 17.5 min gradient by doubling the flow rate. The ammonium acetate in the solvent A was removed. Retention times are a bit shifted. Detection for Histamine and histidine are not great. 

### MS tuning
Tuning was done for 13 compounds. Histamine and Histidine were problematic.
---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Detection of aggressive behaviours in pigs using a RealSence depth sensor"
authors: [Chen Chen, Weixing Zhu, Dong Liu, Juan Steibel, Janice Siegford, Kaitlin Wurtz, Junjie Han, Tomas Norton]
date: 2020-12-06T16:04:00-05:00
doi: "https://doi.org/10.1016/j.compag.2019.105003"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-06T16:04:00-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers and Electronics in Agriculture"
publication_short: ""

abstract: "The aim of this study is to develop a depth image analysis method to automatically detect aggressive behaviours of group-housed pigs. In this work 2 experiments were performed. In each experiment, 8 pigs from 3 pens were mixed for 3 days and then 8 h of video was recorded in each day. In the 24 h data of the first experiment, all the 883 aggressive 3 s-units and manually selected 883 non-aggressive 3 s-units were used as training set. In the 24 h data of the second experiment, all the 856 aggressive 3 s-units and manually selected 856 non-aggressive 3 s-units were used as test set. Firstly, frame-to-frame distance was set and then frame difference method was used to obtain moving pixels. Secondly, moving pixels caused by non-aggressive behaviours were removed by setting threshold of connected area. Number of filtered moving pixels were summed and defined as motion shape index (MSI) in each frame. After dividing all videos into 3 s-units, the maximum, mean, variance and standard deviation of MSI in each unit were extracted as features. Finally, support vector machine (SVM) was used to classify these features in order to detect aggression. Using the proposed algorithm, aggressive behaviours could be detected with an accuracy of 97.5%, a sensitivity of 98.2%, specificity of 96.7% and precision of 96.8%. The results indicate that this algorithm can be used to detect aggressive behaviours of pigs."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Stereo dense depth tracking based on optical flow using frames and events"
authors: [Antea Hadviger, Ivan Marković, Ivan Petrović]
date: 2020-09-25T11:55:44+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-25T11:55:44+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Advanced Robotics"
publication_short: ""

abstract: "Event cameras are biologically inspired sensors that asynchronously detect brightness changes in the scene independently for each pixel. Their output is a stream of events which is reported with a low latency and high temporal resolution of a microsecond, making them superior to standard cameras in highly dynamic scenarios when they are sensitive to motion blur. Event cameras can be used in a wide range of applications, one of them being depth estimation, in both stereo and monocular settings. However, most known event-based depth estimation methods yield sparse depth maps due to the nature of the sparse event stream. We present a novel method that fuses information from both events and standard frames, as well as odometry, to exploit the advantages of both sensors. We propose to estimate dense disparity from standard frames at the point of their availability, predict the disparity using odometry information, and track the disparity asynchronously using optical flow of events between the standard frames. We present the performance of the method through several experiments in various setups, including synthetic data, KITTI dataset enhanced with events, MVSEC dataset, as well as our own stereo event camera recordings."

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

url_pdf: https://www.tandfonline.com/eprint/3CSRX67J67QQU76XCHZP/full?target=10.1080/01691864.2020.1821770
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

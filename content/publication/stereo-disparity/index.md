---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Computationally Efficient Dense Moving Object Detection Based on Reduced Space Disparity Estimation"
authors: [Goran Popović, Antea Hadviger, Ivan Marković, Ivan Petrović]
date: 2018-08-25
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: 2019-09-15T00:04:39+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Symposium on Robot Control"
publication_short: "SYROCO 2018"

abstract: "Computationally efficient moving object detection and depth estimation from a stereo camera is an extremely useful tool for many computer vision applications, including robotics and autonomous driving. In this paper we show how moving objects can be densely detected by estimating disparity using an algorithm that improves complexity and accuracy of stereo matching by relying on information from previous frames. The main idea behind this approach is that by using the ego-motion estimation and the disparity map of the previous frame, we can set a prior base that enables us to reduce the complexity of the current frame disparity estimation, subsequently also detecting moving objects in the scene. For each pixel we run a Kalman filter that recursively fuses the disparity prediction and reduced space semi-global matching (SGM) measurements. The proposed algorithm has been implemented and optimized using streaming single instruction multiple data instruction set and multi-threading. Furthermore, in order to estimate the process and measurement noise as reliably as possible, we conduct extensive experiments on the KITTI suite using the ground truth obtained by the 3D laser range sensor. Concerning disparity estimation, compared to the OpenCV SGM implementation, the proposed method yields improvement on the KITTI dataset sequences in terms of both speed and accuracy."

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

url_pdf: https://arxiv.org/pdf/1809.07986
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

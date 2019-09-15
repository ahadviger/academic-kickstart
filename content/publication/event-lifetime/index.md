---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Stereo Event Lifetime and Disparity Estimation for Dynamic Vision Sensors"
authors: [Antea Hadviger, Ivan Marković, Ivan Petrović]
date: 2019-09-15T00:12:05+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-15T00:12:05+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Mobile Robots"
publication_short: "ECMR 2019"

abstract: "Event-based cameras are biologically inspired sensors that output asynchronous pixel-wise brightness changes in the scene called events. They have a high dynamic range and temporal resolution of a microsecond, opposed to standard cameras that output frames at fixed frame rates and suffer from motion blur. Forming stereo pairs of such cameras can open novel application possibilities, since for each event depth can be readily estimated; however, to fully exploit asynchronous nature of the sensor and avoid fixed time interval event accumulation, stereo event lifetime estimation should be employed. In this paper, we propose a novel method for event lifetime estimation of stereo event-cameras, allowing generation of sharp gradient images of events that serve as input to disparity estimation methods. Since a single brightness change triggers events in both event-camera sensors, we propose a method for single shot event lifetime and disparity estimation, with association via stereo matching. The proposed method is approximately twice as fast and more accurate than if lifetimes were estimated separately for each sensor and then stereo matched. Results are validated on real-world data through multiple stereo event-camera experiments."

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

url_pdf: https://arxiv.org/pdf/1907.07518
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
  focal_point: "Center"
  preview_only: true

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

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Workzone Optimization for Road Networks"
summary: "a GIS-based algorithm to construct optimal workzone for road networks"
authors: []
tags: [Workzone, Optimization]
categories: [Transportation Engineering]
#date: 2016-04-19T11:08:22+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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
> A road network consists of multiple objects that deteriorate over time with different speeds of deterioration. In order to provide an adequate level of service over time, these objects will eventually require interventions. As road managers are trying, in general, to maximize the benefit obtained from the road network, it is in their interest to determine intervention programs, which consist of the grouping of interventions in work zones.

The determination of optimal intervention programs is relatively complicated when considering single objects, but it becomes even more so when considering multiple objects embedded within a network. The objects to be included in the work zones at each time interval depend on many factors, such as the interventions to be executed on the objects, the maximum allowable length of the work zones, the traffic configurations to be used in the work zones and the available financial resources.

| ![](/img/workzone01.png)|![](/img/workzone02.png)
|:---:|:---:|

In order to address this need, we have developed a GIS-based program to determine optimal intervention programs for large infrastructure networks using a linear optimization model The model includes constraints on the amount of available resources, on the length of the work zone, and on the distance between two work zones. A constraint-constructing algorithm is used in order to set up the latter two constraints.

![](/img/workzone03.png)

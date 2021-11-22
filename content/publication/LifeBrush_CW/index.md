---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

weight: 30

title: "LifeBrush: Painting Interactive Agent-Based Simulations"
authors: [Timothy Davison, Faramarz Samavati, Christian Jacob]
date: 2018-10-01
doi: "https://doi.org/10.1109/CW.2018.00017"

# Schedule page publish date (NOT publication's date).
publishDate: 2018-12-27

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2018 International Conference on Cyberworlds (CW)"
publication_short: ""

abstract: 

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

url_pdf: publication/lifebrush_cw/2018_davison_lifeBrush_cyberworlds.pdf
url_code: https://github.com/timdecode/LifeBrush
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=HYLvN2qijeA

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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

{{<autovideo src="teaser.mp4">}}

## Abstract

Building and interacting with 3D agent-based simulations that contain a large number of agents is a significant challenge. What if we want to create an intricate new arrangement of agents, or reconfigure a large number of agents? We present LifeBrush, a cyberworld for interactively painting large and elaborate multi-agent simulations with commodity virtual reality systems that we can then simulate and explore. Our main methodology uses sketch-based discrete element texture synthesis to paint agent arrangements. We define a map to convert agents to elements in this framework when we paint and back to agents when we simulate. Like creating new colors on a paint palette, we create example agent arrangements and configurations in an example palette. We paint new agents into a scene with sketch-based generative brushes. We also use those brushes to reconfigure agents to match examples created in the palette. Then we simulate, pause the simulation and modify the agents with our sketch-based tools. This iteration loop enables new levels of interactivity for the design, simulation, and exploration of agent-based simulations.


{{<youtube HYLvN2qijeA>}}

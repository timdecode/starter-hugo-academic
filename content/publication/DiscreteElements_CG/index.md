---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Interactive example-palettes for discrete element texture synthesis"
authors: [Timothy Davison, Faramarz Samavati, Christian Jacob]
date: 2018-11-09
doi: "https://doi.org/10.1016/j.cag.2018.10.016"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-25T10:39:49-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "Computers & Graphics"
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

weight: 2

url_pdf: publication/discreteelements_cg/2018_davison_preprint-interactive_example_palettes.pdf
url_code: https://github.com/timdecode/InteractiveDiscreteElementPalettes
url_dataset:
url_poster:
url_project:
url_slides:
url_source: 
url_video: https://youtu.be/zkfRPuBbVNw

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

Textures composed of individual discrete elements are found in everything from human-made glass-tilings to forests and tropical coral. We propose an interactive sketch-based system for synthesizing scenes consisting of many discrete element textures. We have implemented an example-palette, a design window where a user can use our sketch-based tools to create discrete element textures and then paint those textures into a scene or back into the example-palette to create new textures. Our interactive sketch-based tools use a new and fast region-growing algorithm that iteratively synthesizes new elements around previously synthesized elements. To support discrete element textures with different scales in the same output, we parameterize our region-growing algorithm on a per-element basis. Our method is capable of synthesizing structured and stochastic example discrete element textures. We explore applications of our system for building virtual worlds (such as for video games) and for sketch-based modeling.


{{< figure src="chapter_rg_teaser.png" caption="System overview: The user creates example arrangments in a palette. Then, the user selects an example arrangment and paints it into the scene. The brushes synthesize element arrangments that are similar to the exemplar." >}}

The video below is a short visualization of the synthesis algorithm. It's based on region-growing, where new elements are added to a growing front, such that the local arrangment of elements is similar to the exemplar. New elements (blue) are added around seed elements (green). This video does not show the optional relaxation step that can sometimes futher improve the quality of the output arrangement at the cost of time performance. 

{{< videofigure src="algorithm_visualization.mp4" caption="Region growing algorithm visualization with (green) seed elements and (dark blue) newly synthesized elements. light-blue and white elements are the final arrangment.">}}

A typical editing session takes place within the Unreal Editor. In the video below, we design an exemplar and then paint it onto a bunny.

{{< videofigure src="coral_bunny_editing_small.mp4" controls="yes" caption="A typical editing session." >}}	


### Youtube
{{<youtube zkfRPuBbVNw>}}

### Gallery
{{<gallery album="projects/paper_det">}}



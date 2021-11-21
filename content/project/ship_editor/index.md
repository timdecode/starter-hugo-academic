---
title: Ship Editor
summary: Design, build and fly spacecraft in VR (bases too).
date: "2021-11-20"

weight: 1

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  preview_only: true
  placement: 1
  caption: An early screenshot.
  focal_point: smart

links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
---

{{<autovideo src="teaser.mp4">}}

ShipEditor was a VR game that I developed from June 2016 to August 2017. I still work on it form time to time. In this game, you design and build space ships and stations.

Features: 

Accurate (only analytical solutions here) orbital mechanics
6-DOF controls–why use clunky fighter joysticks when VR gives you full 6-DOF control over the thrusters
- Thruster simulator–place thrusters on the ship, they consume fuel, the size of the thruster matters. The flight control computer (linear programming solver) computes the exact throttle for each thruster to match the control input. It's what the real space ships do.
- CAD: I wrote a mini VR powered CAD program to design the ship frames, place components etc
- Base construct
- Voxel editing
- Too many things
- Maybe the first ever graph-entity component system (my GitHub repo)


{{< youtube AHtzHkzhVGY >}}

# Screenshots

{{<gallery album="projects/ship_editor">}}
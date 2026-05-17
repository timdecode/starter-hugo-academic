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

ShipEditor (2016–2017) was a VR game for designing, building, and flying spacecraft and bases. You engineer your ships down to the fuel flow rates of each thruster, then take them out into the void.

Features:

- Accurate (analytical-only) orbital mechanics
- 6-DOF thruster controls — VR gives full six-degree-of-freedom control, so no clunky fighter joysticks
- Thruster simulator: place thrusters anywhere on the ship; each consumes fuel based on its size, and a flight control computer (linear-programming solver) computes the exact throttle for each one to match the pilot's input — the way real spacecraft do it
- A mini VR-powered CAD program for designing ship frames and placing components
- Base construction and voxel editing
- Possibly the first-ever graph-entity component system

{{< youtube AHtzHkzhVGY >}}

# Screenshots

{{<gallery album="projects/ship_editor">}}
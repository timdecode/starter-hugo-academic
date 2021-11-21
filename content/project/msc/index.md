---
title: MSc Thesis 
summary: "The huddlge: Cooperate with a machine learning system to beat tough games."


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

{{< video src="teaser.mp4" data-autoplay="" >}}

# Abstract

The huddle is a concept for extending computer games in which the player controls more than one character. It combines several AI methods to allow the player to create a cooperative strategy for his team of characters. It takes away the need for the player to frantically switch his control from character to character to carry out the strategy that he has in mind. The player enters the huddle from a saved game state where he provides the key ideas of a strategy in the form of situations that his characters can be in andactions for those situations (SAPs). Based upon these ideas, a learner fills in the missing details by adding additional SAPs to create a complete strategy that can be used in the real game.

The learning component uses a simulation of the real game, with models of the non-player characters created from the observed behaviours of those characters, in order to evaluate candidate solutions. When a solution is found, the player is given the opportunity to take it to the real game and have the behaviour of his characters replaced by the combined strategy created by himself and the huddle.

The huddle was evaluated with a fantasy-themed role playing game. It was shown that the huddle allowed the player to focus on developing a strategy without taking away the requirement for him to create the key ideas for that strategy.

{{< youtube um-2z5lTdbg >}}

# Screenshots

{{<gallery album="projects/msc">}}
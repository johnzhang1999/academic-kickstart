---
title: Carcassonne (Board Game)
summary:  A multi-player tile-laying board game. GUI constructed with Java Swing.
tags:
- Java
- GUI
- Game
date: "2020-04-29T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: A screenshot of an ongoing Carcassonne game
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# Gameplay

First enter a number as the total number of players of the game in the prompt to start the tame. The tile on the top right corner is the current tile of the round. The current player (as indicated by the color of the available tile positions on the board) must rotate the current tile and place it at a suitable location on the board. Then the player will decide to optionally place a meeple on the newly placed tile by selecting the location in the combo box. When the player decides the position to place a meeple (or not to place a meeple), click the next button for next round. The game status (scores and remaining meeples of each player) will be updated on the top left corner as each round ends. When the game ends, a dialog will pop up and indicate the winner of the game.
---
title: Chess Clone
subtitle: Online chess
image: assets/img/portfolio/chess/board.PNG
alt: Chess board

caption:
  title: Chess Clone
  subtitle: Online chess
  thumbnail: assets/img/portfolio/chess/board_thumb.png
---


As an exercise, I wanted to make a simple clone of chess with support for online matches. I reused many of the assets from my previous game (Toad Tactics) and was able to get most of the implementation down within a week. Most of that time was spent learning about the niche rules of chess and figuring out an architecture to support them. I ended using a cloneable gamestate which allowed testing possible moves to ensure they would not leave a player checked. This was a fun one coming off of a large scope game and it felt like my lessons from developing the previous game were paying off.
{: style="text-align: justify;"}

[Download](https://github.com/yochie/ChessClone/releases){:.btn .btn-primary .btn-xl .text-uppercase}

#### Example game

![Full game](assets/img/portfolio/chess/gifs/full_game.gif){: width="100%" }

#### Mechanics

##### Legal move filter
![Legal move filter](assets/img/portfolio/chess/gifs/legal_moves.gif){: width="100%" }

##### Promotion
![Promotion](assets/img/portfolio/chess/gifs/promotion.gif){: width="100%" }

##### Castling
![Castling](assets/img/portfolio/chess/gifs/castling.gif){: width="100%" }

##### En passant
![En passant](assets/img/portfolio/chess/gifs/passant.gif){: width="100%" }



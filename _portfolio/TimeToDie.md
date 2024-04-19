---
title: Time to Die
subtitle: 2D platformer with a twist
image: assets/img/portfolio/time_to_die/cover_compressed.png
alt: 

caption:
  title: Time to Die
  subtitle: 2D platformer with a twist
  thumbnail: assets/img/portfolio/time_to_die/cover_thumb.png
---
For this game,  I was inspired by Spelunky, a rogue like platformer where interaction between objects in the game makes for unexpected and interesting chains of events. Rather than go for the typical goal of reaching the exit, the twist here is that the objective is to achieve death as quickly as possible while enduring as little pain as possible in the process.
{: style="text-align: justify;"}

My goal here was to learn about the Unity physics engine, so while most platformers seem to opt for manually setting up an artificial physics system, I stuck to using Rigidbody physics. I also believed that could be a suitable framework for generating interesting interactions between gameobjects, at the cost of clean and tight gameplay. The end result is somewhat janky gameplay but I believe there is some originality and potential behind this idea. I would have liked to spend more time here building some procedurally generated maps and setting up more interactions.
{: style="text-align: justify;"}

[Download](https://github.com/yochie/TimeToDie/releases){:.btn .btn-primary .btn-xl .text-uppercase}

#### Mechanics

##### Arrow traps
Classic arrow traps that trigger when anything gets in front of them (including enemies or arrows from other traps). The arrows can be deflected by player attacks.
{: style="text-align: justify;"}
![Arrow traps](assets/img/portfolio/time_to_die/gifs/arrow_traps.gif){: width="100%" }

##### Spike traps
Slow player movement and trap enemies.
{: style="text-align: justify;"}
![Spike traps](assets/img/portfolio/time_to_die/gifs/spike_traps.gif){: width="100%" }

##### Enemies
They patrol any platform they happen to stand on. They can't be killed but they can be knocked back and temporarily ghosted by player attacks. 
{: style="text-align: justify;"}
![Enemies](assets/img/portfolio/time_to_die/gifs/enemies.gif){: width="100%" }


##### Fall damage
One of the easier ways to read a quick end, but you need to be efficient at the platform game to find good jumping off points.
{: style="text-align: justify;"}
![Fall damage](assets/img/portfolio/time_to_die/gifs/fall_damage.gif){: width="100%" }

##### Scoring
Half of the score is based on how long it took to complete a stage based on some default average. The other half is based on the pain that is taken before death out of the maximum.
{: style="text-align: justify;"}
![Scoring](assets/img/portfolio/time_to_die/gifs/score.gif){: width="100%" }


#### Libraries / Assets
* [Platformer Set](https://assetstore.unity.com/packages/2d/environments/platformer-set-150023)
* [Sunny Land](https://assetstore.unity.com/packages/2d/characters/sunny-land-103349)
{: style="text-align: left;"}





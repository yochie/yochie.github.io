---
title: Believe
subtitle: 3D gliding
image: assets/img/portfolio/believe/cover.png
alt: 

caption:
  title: Believe
  subtitle: 3D gliding
  thumbnail: assets/img/portfolio/believe/cover_thumb.png 

---

As a first foray into 3D games, I chose to make a classic gliding mini game where the player aims at passing through a series of rings. I was inspired by flight mechanics in games like Just Cause, Super Fly and Cube World where you manage different resources (stamina, speed, altitude) in ways I found particularly gratifying. Most of the work here went into the flight controller itself, making sure it felt somewhat physically possible all the while remaining satisfying to control. I also chose to include a wind mechanic to add to the resource management aspect. This was a great opportunity to brush up on my vector maths, learn about quaternions and get a feel for 3D games in general. 
{: style="text-align: justify;"}

[Download](https://github.com/yochie/believe/releases){:.btn .btn-primary .btn-xl .text-uppercase}

#### Mechanics

##### Directional Rings
Rings grow in size until they timeout, whereby they decrement the score and shrink to nothingness. They must be traversed in the indicated direction. A spawner ensures the rings are spawned relatively aligned with eachother and within reasonable distances.
{: style="text-align: justify;"}

![Rings](assets/img/portfolio/believe/gifs/rings.gif){: width="100%" }


##### Loss of lift
While the player is pitched upwards, they gradually deccelerate until their speed is below some threshold, at which point their pitch is forced downwards.
{: style="text-align: justify;"}

![Loss of lift](assets/img/portfolio/believe/gifs/loss_of_lift.gif){: width="100%" }

##### Wind
The wind direction (displayed bottom right) modulates the speed decay that occurs while pitching upwards. This allows the player to rise while aligned with the wind.
{: style="text-align: justify;"}


![Wind](assets/img/portfolio/believe/gifs/wind.gif){: width="100%" }


#### Libraries / Assets

* Cinemachine
* [Low Poly Vegetation Kit Lite](https://assetstore.unity.com/packages/3d/environments/low-poly-vegetation-kit-lite-176906)
* [Flying System](https://assetstore.unity.com/packages/p/flying-system-254446) (3D models only)
{: style="text-align: left;"}


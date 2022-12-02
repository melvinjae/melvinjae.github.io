---
layout: essay
type: essay
title: "Designing a Nice Pattern"
# All dates must be YYYY-MM-DD format!
date: 2022-12-01
published: true
labels:
- Design Pattern
- Software Engineering
---

## Pattern Recognition
Pattern Recognition is an ability human brains have that finds patterns and figures out what those patterns lead to. An example of this can be seen in modern Tetris games, which I'm currently into right now. In modern Tetris, the goal is to versus an opponent and send as much garbage as you can to them, this is usually done by clearing lines in your own board. A strong technique in the game is called a T-Spin Double, or TSD for short. This ties into pattern recognition by utilizing a template which in this case is a empty space with a T shape with an overhang which can be viewed in the images below.
<div class="text-center p-4">
<img width="75px" src="https://cdn.discordapp.com/attachments/1019876231405109261/1048143406108508171/image0.jpg" alt="">
<img width="75px" src="https://cdn.discordapp.com/attachments/1019876231405109261/1048143396490973225/image0.jpg" alt="">
<img width="75px" src="https://cdn.discordapp.com/attachments/1019876231405109261/1048143361988644894/image0.jpg" alt="">
</div>

## Actual Design Patterns (not tetris)

Now how does Tetris relate to design patterns in software development? Well design patterns are a general, reusable solution to a commonly occurring problem in software design and is a template that can be used in many different situations. Just like how there is a general template in the TSD, being an empty T space and a general, reusable solution being an overhang.

## My Relationship With Design Patterns
We did not get along well as I was unable to understand it fully. Some concepts of design patterns I have used were Factory, Observer, and Singleton. These were implemented in my Critter game, that can be viewed in the projects section of the portfolio
#### Just a Factory Worker
In my Critter game, I created physical objects that fall under the same concept of movable entities, but each object moved different from each other.
#### Only an Observer
In the same game, I had multiple event handlers that processed score and the player taking damage. The floor had an OnCollisionEnter handler that reacted if a player had went into the collection area and offloaded any saved critters. There was also another OnCollisionEnter handler that reacted when a collectable critter was touched by the player.
#### Eventually became Singleton
The Singleton used in my game was to keep track of score... Which I did not end up correctly implementing because lack of understanding. I somewhat implemented a singleton correctly in another game I worked on, but it still had its issues.

### Thoughts On Design Patterns as a whole
I have only scratched the surface on what design patterns are, but the concept resonates in me because I like to reuse viable code whenever possible as it seems efficient to me.
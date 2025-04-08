---
layout: post
# If your post title is longer or more complicated
# than can be represented in the filename, uncomment the following line
# and specify a custom title
# title:  "630C3N7R15M"

categories: 
- Contribution

# Enter your name below
author: Thomas Roman
---

For my Humanitarian Free and Open Source Software Development class, I have decided to contribute to the [Gamer Church](https://gamer.church/) website.

## What is Gamer Church?
"700 Trillion Lives Ago, the game of the world was created. Mixing life with radical rightness and finite intelligibility, everything was born. No one understands why or when or how or what or who or why. Fighting against the tide of incredulity and unstability is futile. Everything, all of it, from now until forever and going all the way back to bunk, is irrelevant. Time is irrelevant. We cannot fight it, we cannot process it, we cannot be anything to anyone. We have no reason to live, so they said, but they were wrong. We live for a purpose.

Ludere Sanctum Ludum, to play the Holy Game."

Gamer Church is an experimental gaming website. The website contains a forum where people post testimonies relating to the central vibe with which the church operates on. It's pretty abstract, but for our purposes it's a hub of indie games connected by hidden secret codes.

## How I found Gamer Church
For years I've been a fan, member, and contributor to the Chunk Printing and Publishing community. This community produces zines and music CDs through collaborative effort online. This year, a new project was announced from the community leader, Angelboy Discoman, and that project is Gamer Church.

## Joining the community
I reached out to a colleague who I knew was on the project team. He put me in contact with the lead developer, who invited me to the discord server.
The server is full of people making games and sharing ideas.

## Joining the community
I reached out to a colleague who I knew was on the project team. He put me in contact with the lead developer, who invited me to the discord server.
The server is full of people making games and sharing ideas.

## Making the Initial Prototype
I tend to be pretty fast with new ideas, so I just shared the first thoughts I had:
"anyway the idea that immediately came to mind for a tiny game is one where you control the earth and the sun is attracted to you with gravity and so you use this to guide the sun to collide with space demons, the demons burn up when they hit the sun.
there is risk and reward because your weapon can also kill you, but you need it to reduce the number of space demons because those kill you on contact too.
Also I guess this endorses geocentrism, which is a bit silly, but games are forfun. If yall think of other approaches to the context of this mechanic lemme know."
Some people liked the idea so I programmed the gameplay. I used Godot for this and basic physics using Newton's equation for gravitational attraction (G*mass1*mass2)/(distance^2)
Here's how that code looks currently:
![Code Snippet for Sun Gravity](https://imgur.com/GPrcVvp)

## Collaborating with an artist
I started a thread for this game and called it, "630C3N7R15M"
After seeing the prototype, Odin, creator of the Bug Saga zines, suggested a style for the game based on medieval art. I thought this style would fit nicely and they began to create assets for the game and suggest various ideas for the gameplay. One idea they suggested was the moon, which allows the player to deflect incoming demons. As we work together we continue to refine the game into something worthy of a place in the church.
![Odin's draft title screen](https://imgur.com/HvntvKR)

## Our Progress so Far
So far we've implemented 2 demons, the earth, the sun, and the moon. Odin has made fantastic art for all of the games features thus far and he's got more stuff which I'm excited to implement and share.
You can view a preview of the gameplay [here](https://youtu.be/4M09jGWllIU)

## Future Plans
I have playtested the game now at the RIT Game Dev Club and plan to make some tweaks to the game, such as changing the sun to an Area2D and doing away with its bouncy effect. I also plan to add the following features:
- Titlescreen and respawn menu
- new enemies
- moon variations which act as powerups

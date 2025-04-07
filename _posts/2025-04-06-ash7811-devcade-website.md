---
layout: post
# If your post title is longer or more complicated
# than can be represented in the filename, uncomment the following line
# and specify a custom title
# title:  "Sample Blog Post"

categories: 
- Contribution

# Enter your name below
author: Andrew H
---


# Introduction
My contribution is towards a react rewrite of the [devcade website](https://github.com/ComputerScienceHouse/devcade-website/) for Computer Science House. Having been a CSH upperclassman for over a year, I wanted to contribute in some form to the long-term projects the organization hosted. Of these is Devcade, the arcade machine featuring various games created by CSH members. Their current website is written in Flask, and [a branch](https://github.com/ComputerScienceHouse/devcade-website/tree/react-rewrite) existed for rewriting the website in React in response to [an open issue](https://github.com/ComputerScienceHouse/devcade-website/issues/67). This endeavor had been dormant for some time, so I decided to revive it, even if this isn't the best thing to do as shown by the CommArch assignments. This undertaking goes beyond simply fulfilling a contribution, and acts as a longer project I can revisit and recruit others to join.

It was simple to get up to speed with how to navigate the project, as the `README.MD` gave a simple explanation on how to run it, and I was familiar with the structure of React projects in the first place.

# The Issue
There were many pages I could choose, but I decided to choose the game list page, which was empty at the time.
![image](https://github.com/user-attachments/assets/501f9e1f-89bb-42cb-aa93-c45ff28a631d)
My end goal is to implement the game list loading, which will look roughly similar to the page from the current devcade website. https://devcade.csh.rit.edu/catalog
![image](https://github.com/user-attachments/assets/d6beb49f-7448-42b4-9c85-636ce30a513b)
Before doing any styling, I was to simply fetch the game list and display it on the page. This seemed simple enough, but I had to actually run the project before anything else. This proved to be more inconvenient than expected, requiring me to disable SSO to log in, as enabling it would cause errors. I also needed to deal with the CORS policy that blocked me from fetching from an online link, which simply involved copying the fetch results to a local file for testing. After those hurdles, the process was simple, and the result is shown below.
![image](https://github.com/user-attachments/assets/bc7d494f-059c-4c92-81c0-c5d443b8f309)
To have these changes merged, I am to ask the person who directed me to this issue in the first place, as they are a current contributor. This is currently still in progress.

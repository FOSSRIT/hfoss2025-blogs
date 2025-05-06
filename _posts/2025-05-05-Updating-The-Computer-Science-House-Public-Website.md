---
layout: post
categories: 
- Contribution
author: Marcus Otto
---

## Thing I Contributed To

[CSHPublicSite](https://github.com/ComputerScienceHouse/CSHPublicSite)

> A project that serves as the public-facing website for Computer Science House, showcasing events, members, and the community's history.

### Why I Picked It

This was my first contribution to a Computer Science House (CSH) open source project. Even though I’ve been a member of CSH for a while, I hadn’t previously taken the time to get involved in any of our open source projects. I chose this one because I’ve been browsing the [CSHPublicSite repo](https://github.com/ComputerScienceHouse/CSHPublicSite) for a while, and I noticed a section on the site that mentioned "one project per freshman",  a tradition that hasn’t been active for some time. Since it misrepresents what new members actually experience, I figured this would be a good first fix to get my feet wet with contributing.

### Getting Involved

The process of jumping in was smoother than I expected. The readme made it clear how to install dependencies and preview the site locally using [Jekyll](https://jekyllrb.com/docs/). I followed the setup instructions and was able to spin up a local server. What stood out to me was that the project was well-organized. SCSS partials were modular, assets were clearly separated, and the HTML was easy to follow. I didn't have to dig through complex React states or JS-heavy templates. It felt very welcoming to a beginner contributor. The maintainers of the project were also responsive to me, but I am a member of CSH so that may affect how easy it is to contribute.

### The Issue
While reading through the about page, I noticed that there was still a section about "one project per freshman". This isn’t current anymore, and having it publicly listed could mislead prospective members. There wasn’t a pre-existing GitHub Issue filed for this.

### The Fix
I removed the HTML section referencing the outdated freshman project requirement from the homepage content. Specifically, I edited the about/projects.html file and deleted the paragraph block.

![Fix](/hfoss2025-blogs/assets/images/mco9734/fix.png)

Here’s the relevant [commit](https://github.com/ComputerScienceHouse/CSHPublicSite/commit/8eefa80d0ea59f055c79db2df572dbe24c03874b)

The [PR](https://github.com/ComputerScienceHouse/CSHPublicSite/pull/360) was titled:

Deleted one project per freshman to align with current practice

And here’s a snippet of my pull request comment:

“We haven't done one project per freshman since I've been here, so it would probably be a good idea to remove it from the pubsite.”

This is what the website looked like before my changes.
![Before](/hfoss2025-blogs/assets/images/mco9734/before.png)

This is what it looked like after my changes.
![After](/hfoss2025-blogs/assets/images/mco9734/after.png)

### Was It a Solid Effort?
Yes, I believe this contribution was appropriate and valuable. It didn’t require a complex code change, but it improved the accuracy and professionalism of our public-facing content. I verified the local build after the change and checked for any rendering issues.

### Was It Accepted?
Not yet, I am still awaiting a response from our webmasters.
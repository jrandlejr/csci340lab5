---
layout: post
title: "Lab 3 - Jekyll Styling Reflection"
date: 2026-02-02 20:00:00 -0600
author: James Randle Jr
---

Lab 3 was all about making my Jekyll blog look better and more like me.

The main things I did were swapping the date and title order in posts, adding myself as author, creating new pages that automatically show up in the nav bar, adding an external link, and styling the site with custom CSS using my fraternity colors (crimson and cream).

Here are some things that were **new** to me:
- Editing files inside _layouts and _includes to change how posts and the header look
- Overriding the Minima theme styles by adding rules at the bottom of assets/css/style.scss
- How pages placed in the root directory automatically get added to the navigation bar
- Using flexbox and other CSS to try positioning elements (even if the logo didn't end up working)

Parts I struggled with:
- The "Invalid YAML front matter" error in style.scss kept showing up even when the file was basically empty. It turned out to be mostly a VS Code thing, not a real Jekyll build problem.
- Getting changes to show up consistently; I had to restart the server a lot.
- Trying to add the Kappa logo next to the blog title didn't work out the way I wanted, so I removed it.

Things that still don't fully make sense yet:
- Exactly why style.scss needs the --- front matter when other CSS/SCSS files don't
- The full rules for how Jekyll decides which styles (theme vs my overrides) win
- The difference between when I should edit a layout/include file vs just use CSS

I'm really looking forward to:
- Adding more custom touches in future labs
- Starting the database parts of the class and blogging about SQL and web systems
- Making the site responsive and mobile-friendly

Two resources that helped:
- The [Minima theme on GitHub](https://github.com/jekyll/minima) for seeing what I could customize
- Dr. Goadrich's [CSCI 340 step-by-step labs](https://hendrix-cs.github.io/csci340/) — super clear instructions

Here are two screenshots of my changes going from the original minima white and black background to a nice crimson and cream feeling; paying homage to my fraternity Kappa Alpha Psi:

![My Alt Text]({{ '/assets/images/crimson-header.png' | relative_url }})

![My Alt Text]({{ '/assets/images/crimson-post-example.png' | relative_url }})

This lab took some troubleshooting, but now the blog actually feels personal.
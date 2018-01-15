---
title: Microsoft Sculpt Mouse macOS Gesture Setup (updated)
comments: true
layout: post
type: text
description: A How-To on my custom Microsoft Sculpt Comfort Mouse setup for Macs using Karabiner.
---

Previously I wrote about how I set up my [Microsoft Sculpt Comfort Mouse](https://www.microsoft.com/accessories/en-us/products/mice/sculpt-comfort-mouse/h3s-00003)'s Windows key to work with my Mac. Since updating to Sierra and High Sierra, this solution has broken. Thus I set out to find a new solution and I finally have one. I was not able to get the full features of what I had in my former post, but I actually prefer the new mappings. 

To fix the my previous solution, I had to update to the new version of Karabiner, [Karabiner-Elements](https://pqrs.org/osx/karabiner/). This changes things drastically, and so I had to redo my whole experiment of looking at the EventViewer and reading in the activated key codes and modifiers. Long story short, I created a new custom complex modification to add to the software. That can be imported to your Karabiner-Elements by clicking [here](karabiner://karabiner/assets/complex_modifications/import?url=http://www.drewdunne/karabiner/ms_sculpt_mouse.json). 

The new mappings do the following:

- Press ==> **Launchpad**
- Swipe up ==> **Spaces Right**
- Swipe down ==> **Spaces Left**

Again, anyone can customize these to their liking. The JSON documentation for Karabiner-Elements can be found [here](https://pqrs.org/osx/karabiner/json.html). The installation instructions from GitHub are [here](https://github.com/pqrs-org/KE-complex_modifications). Good luck!

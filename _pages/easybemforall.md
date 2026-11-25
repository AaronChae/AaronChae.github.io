---
layout: page
title: EasyBEMforAll
description: Building energy modeling in plain words, from a floor plan to an EnergyPlus model.
permalink: /easybemforall/
nav: true
nav_order: 2
---

Easy BEM for All is a web tool I am building that turns a floor plan into a building energy model. It asks plain questions about the building instead of using simulation jargon, and builds an EnergyPlus model behind the scenes.

Energy modeling can tell you a lot about a building, but the usual tools take a lot of training before you get a first result. I want people who know the building, even if they don't know the software, to be able to make a reasonable model and see where the energy goes.

#### What it does

- Walks you through 11 short steps, from location and building use to rooms, walls and windows, heating and cooling, lighting, temperatures, and energy source, then runs the simulation and shows the results.
- Lets you trace the building outline over a floor plan (PDF or image) and see the building in 3D with the sun for any day and time.
- Fills in typical values for anything you skip, so you can run a first simulation early and refine it later.
- Gives quick checks along the way, such as how much heat leaks out on a cold day, and an annual daylight analysis with Radiance.
- Shows energy use by floor, by end use, and by month, and compares the results with your meter data if you have it.
- Saves your work in the browser or to a file you can open again later.

#### Who it's for

Anyone who wants a first look at a building's energy use without becoming a modeling expert, such as architecture students, designers in early design, and building owners or facility teams.

It is still in development. The demo below shows the current version.

<video src="{{ '/assets/video/easybem-demo.mp4' | relative_url }}" class="img-fluid rounded z-depth-1" controls controlslist="nodownload" preload="metadata" playsinline oncontextmenu="return false;" title="EasyBEMforAll demo video"></video>

<p class="small text-muted">The demo video and the text on this page are &copy; 2026 Myeongwon Chae. Please do not copy, screen-record, or repost them without my permission.</p>

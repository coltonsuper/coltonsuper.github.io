---
layout: post
title: Training attempt 1 - no filter
date: 11/19/26
---

This was the first attempt at retraining GOFLOW on equatorial Pacific ROMs data. I think the model is doing an ~ok job, but on the walls something goofy is going on. I plan to retrain again with a filter and hopefully see better results. 

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe
    src="https://www.youtube-nocookie.com/embed/7q0NLIYjMJI"
    title="Training test vorticity"
    style="position: absolute; inset: 0; width: 100%; height: 100%; border: 0;"
    allowfullscreen>
  </iframe>
</div> 

stage0 training stats:
gradR^2 = 0.4489, velR^2 = 0.951, spec = 20.6340

stage1 training stats:
gradR^2 = 0.2397, velR^2 = 0.9393, spec = 2.5571
---
title: "UO2 MOOSE Simulation"
date: 2025-01-11
description: "My experience doing multiphysics MOOSE simulations to examine stress, fracturing, and temperature during operation."
tags: []
categories: ["Research", "Code"]
draft: false
---

# Thanks for dropping in!

## What did I learn from this project?

This is a slightly older project that I collaborated on using MOOSE in sophomore year. It was my first introduction to multiphysics modeling and simulation, which is now one of my key interests. It also showed me the importance of understanding software from a (slightly) lower level of code, a lesson I have used a lot recently to help with my current research project.

## Basis

The simulation is based on a 2D slice of a fuel rod with cladding. The fuel itself is a simple UO2 pellet, which we simulate over a moderately large time frame to see how it fractures. This can be contrasted with other simulations that have similar parameters but with changes in material properties for the pellet; this would allow further examination of how different fuel materials hold up structurally over the span of operation.

## Video Demonstrations

I have embedded two videos below that unfortunately do not seem to work all that well at the moment. You will notice 'jumps' in both; that is because I am normalizing the data at that time so the rate of change is plain to see. I prioritized this over the absolute data scaled over the whole time because that scale makes the final data look somewhat homogenous.

The UO2 fracture with cladding was a video taken of the exodus file from a simulation of the radial stress, radial strain, hoop stress, and hoop strain. In this case, the simulation shows radial stress— the lines you see are where cracks form in the pellet.

The UO2 mechanics with cladding was a video taken of the temperature distribution over operation. Due to the cladding being at a much lower temperature than the center of the pellet, the temperature profile did not change much after the initial time steps.

### UO2 Fracture with Cladding

{{< video src="/videos/uo2fracture_with_cladding.mp4" >}}

<video controls width="800">
  <source src="/videos/uo2fracture_with_cladding.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### UO2 Mechanics with Cladding

{{< video src="/videos/uo2mechanics_with_cladding.mp4" >}}

<video controls width="800">
  <source src="/videos/uo2mechanics_with_cladding.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
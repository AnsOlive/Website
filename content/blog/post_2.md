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

This is a slightly older project that I used MOOSE for in sophomore year. It was my first introduction to multiphysics modeling and simulation, which is now one of my key interests. It also showed me the importance of understanding software from a lower level, a lesson I have used a lot recently to help with my current research project.

## Basis

The simulation is based on a 2D slice of a fuel rod with cladding. The fuel itself is a simple UO2 pellet, which we simulate over a moderately large time frame to see how it fractures. This can be contrasted with other simulations that have similar parameters but with changes in material properties for the pellet; this would allow further examination of how different fuel materials hold up structurally over the span of operation.

## Video Demonstrations

I have embedded two videos below that unfortunately do not seem to work all that well at the moment. The UO2 fracture with cladding was a video taken of the exodus file from a simulation of the radial stress, radial strain, hoop stress, and hoop strain. In this case, the simulation shown was how these factors induced the pellet to crack over time.

The UO2 mechanics with cladding was a video taken of the temperature distribution over operation. You will notice that it does not change much over time. This is because the time steps were fairly large in comparison to the lifetime of a neutron and that the pellet had the highest temperatures by far. Due to the cladding being at a much lower temperature than the center of the pellet, the temperature profile did not change much. The simulation also normalized each time step with the maximum and minimum temperatures for that time- another reason why the change seen is minimal.

### UO2 Fracture with Cladding

<video controls width="640" height="360">
  <source src="/videos/uo2fracture_with_cladding.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### UO2 Mechanics with Cladding

<video controls width="640" height="360">
  <source src="/videos/uo2mechanics_with_cladding.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
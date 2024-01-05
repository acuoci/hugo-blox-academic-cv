---
title: OpenSMOKE++
summary: A C++ framework for numerical simulations of reacting systems with detailed kinetic mechanisms.
tags:
  - Kinetics
  - Numerical modeling
date: '2024-01-05T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: https://www.opensmokepp.polimi.it/

image:
  caption: OpenSMOKE++ Logo
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/@OpenSMOKEpp
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

OpenSMOKE++ is a general framework developed by the CRECK Modeling Lab for **numerical simulations of reacting systems with detailed kinetic mechanisms**, including thousands of chemical species and reactions.

1. **User-friendly**: OpenSMOKE++ framework can handle simulations of ideal reactors, shock-tubes, rapid compression machines, laminar 1D flames and multidimensional reacting flows
2. **Fast**: OpenSMOKE++ adopts advanced numerical techniques able to reduce the computational cost, without sacrificing the accuracy and the robustness of the calculations
3. **Free**: OpenSMOKE++ is completely free for Academic use! We only ask you to register on our website and cite OpenSMOKE++ in your publications

OpenSMOKE++ can handle simulations of ideal reactors, shock-tubes, rapid compression machines, 1D laminar flames and multidimensional reacting systems, and it provides useful numerical tools such as the sensitivity and rate of production analyses.

OpenSMOKE++ is distributed in three main packages.

1. **OpenSMOKE++ Suite**: Simulation of ideal reactors (batch, plug-flow, perfectly stirred reactors), shock-tubes, rapid compression machines, laminar 1D flames (freely propagating and burner stabilized flames, counter-flow diffusion flames)
2. **OpenSMOKE++4OpenFOAM**: Solvers for steady-state and unsteady reacting flows in arbitrarly complex multidimensional geometries with detailed kinetic mechanisms (based on OpenFOAM)
3. **DoctorSMOKE++**: Automatic reduction of detailed kinetic mechansims to a skeletal level, to allow their use in large scale CFD simulations. DoctorSMOKE++ is currently under testing. We plan to release it in a few months.

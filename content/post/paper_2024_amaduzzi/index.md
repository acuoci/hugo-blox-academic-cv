---
title: "Accelerating reactive CFD: Automated Adaptive Chemistry for LES of Turbulent Reacting Flows"
subtitle: "Our recent paper introduces an innovative approach, based on the SPARC technique, which leverages machine learning algorithms to adaptively select a reduced kinetic mechanism for each computational cell in Large Eddy Simulations (LES) of turbulent reacting flows. This innovative methodology significantly reduces the computational cost of LES, offering a promising avenue for more efficient and accurate simulations of turbulent reacting flows, particularly in combustion research."

# Summary for listings and search engines
summary: "Our recent paper introduces an innovative approach, based on the SPARC technique, which leverages machine learning algorithms to adaptively select a reduced kinetic mechanism for each computational cell in Large Eddy Simulations (LES) of turbulent reacting flows. This innovative methodology significantly reduces the computational cost of LES, offering a promising avenue for more efficient and accurate simulations of turbulent reacting flows, particularly in combustion research."

# Link this post with a project
projects: []

# Date published
date: '2024-01-05T00:00:00Z'

# Date updated
lastmod: '2024-01-05T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic
  - CFD

categories:
  - CFD
---

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 10px; border-radius: 4px; color: #3c763d; background-color: #dff0d8; border-color: #d6e9c6;">
Amaduzzi R., D'Alessio G., Pagani P., Cuoci A., Malpica Galassi R., Parente A.   

Automated adaptive chemistry for Large Eddy Simulations of turbulent reacting flows     
Combustion and Flame, 259, 113136 (2024)   
DOI: [10.1016/j.combustflame.2023.113136](https://www.sciencedirect.com/science/article/pii/S0010218023005114)      
</div>





In this paper, we introduced a novel approach called **Sample-Partitioning Adaptive Reduced Chemistry (SPARC) for Large Eddy Simulations (LES) of turbulent reacting flows**. The main novelty of this work lies in the application of machine learning (ML) algorithms to reduce the computational cost of LES by adaptively selecting a reduced kinetic mechanism for each computational cell. 

The SPARC approach involves two main steps carried out in a preprocessing phase: first, the partitioning of the training database into coherent groups of points in the thermochemical space using unsupervised ML algorithms, and second, the kinetic reduction, which generates a library of simplified kinetic mechanisms for on-the-fly use. Then, during the CFD simulation, the on-the-fly classification step assigns a skeletal mechanism from the library built in the preprocessing stage to each computational cell. The SPARC approach has been validated in the context of CFD simulations of unsteady laminar flames, employing both 2D and 1D simulations to generate the training dataset.

Here, we extended this technique, to LES of turbulent flows. The use of machine learning algorithms and model reduction methods in the proposed approach provides a **fully automated strategy for performing Large Eddy Simulations (LES) with adaptive chemistry**, offering a promising avenue for more efficient and accurate simulations of turbulent reacting flows, which is essential for the development of efficient, stable, and non-pollutant combustion technologies.
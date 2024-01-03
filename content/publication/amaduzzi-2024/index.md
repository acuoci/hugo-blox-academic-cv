---
title: Automated adaptive chemistry for Large Eddy Simulations of turbulent reacting
  flows
authors:
- Ruggero Amaduzzi
- Giuseppe D'Alessio
- Pietro Pagani
- Alberto Cuoci
- Riccardo Malpica Galassi
- Alessandro Parente
date: '2024-01-01'
publishDate: '2024-01-03T15:58:18.111238Z'
publication_types:
- article-journal
publication: '*Combustion and Flame*'
doi: 10.1016/j.combustflame.2023.113136
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85175649649&doi=10.1016%2fj.combustflame.2023.113136&partnerID=40&md5=9b88a081e10947dc99c0daaaeb2c839f

# Display this page in the Featured widget?
featured: true

abstract: 'Large Eddy Simulations (LES) of turbulent reacting flows carried out with detailed kinetic mechanisms have a key role for the discovery of the physical and chemical processes occurring in combustion systems, and are essential for the development of efficient, stable, and non-pollutant technologies. Nevertheless, these simulations require a large amount of computational resources, making their utilization for large-scale systems, such as industrial burners and gas turbines, impractical. In this work, we combine state-of-the-art machine learning algorithms and model reduction methods to deliver a fully automated strategy for performing LES with adaptive chemistry. This strategy is based on the Sample-Partitioning Adaptive Chemistry (SPARC) algorithmic procedure, which consists of four steps: the generation of a training dataset, its partitioning in clusters, the generation of a set of reduced chemical mechanisms specifically tailored to each cluster and, lastly, the numerical simulation of the case of interest with adaptive chemistry enabled by an on-the-fly classification of every grid point. The SPARC approach has already been demonstrated to substantially reduce the computational effort of reactive flows simulations. However a non-negligible level of user interventions is needed, upon which the method’s success critically depend. Therefore, with the goal of boosting the performance of this workflow and minimise the user-specified degrees of freedom, we plug in and exploit the Local Principal Component Analysis augmented with an automated Bayesian-optimised search for optimal clustering solutions, and the Computational Singular Perturbation method with an additional layer of automation based on the Tangential Stretching Rate for minimally-sized reduced mechanisms. We employ a cheap and easy-to-generate 1-dimensional-flames training database and we demonstrate the efficiency, accuracy and robustness of this strategy with an application to LES of the Adelaide Jet in Hot Coflow (AJHC) burner, a turbulent reacting flow exhibiting intense turbulence-chemistry interactions.'

# Summary. An optional shortened abstract.
summary: 'This study introduces a novel approach to Large Eddy Simulations (LES) of turbulent reacting flows, crucial for understanding combustion systems. By integrating machine learning and model reduction methods, the Sample-Partitioning Adaptive Chemistry (SPARC) algorithm automates LES with adaptive chemistry. Enhanced with Local Principal Component Analysis and Computational Singular Perturbation, the strategy minimizes user intervention, boosting efficiency. The method's effectiveness is demonstrated in simulating the Adelaide Jet in Hot Coflow (AJHC) burner, showcasing reduced computational effort and robust performance in complex turbulent-reacting flows.'

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - acceleration

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

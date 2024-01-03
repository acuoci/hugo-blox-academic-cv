---
title: Accelerating reactive-flow simulations with detailed kinetics in OpenFOAM

event: OpenFOAM & Combustion Simulation Webinar
event_url: https://blog.nus.edu.sg/ofcw/home/

location: Virtual seminar
# address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: Accelerating reactive-flow simulations with detailed kinetics in OpenFOAM
abstract: 'The numerical modeling of multi-dimensional reactive flows with realistic/detailed kinetic mechanisms (including hundreds of species and thousands of reactions) represents a challenging problem and places severe demands on computational resources, because of the number of strongly coupled equations to be solved and their high non-linearity and stiffness. 
This talk presents and discusses the main numerical techniques adopted in the CRECK Modeling Lab at Politecnico di Milano for accelerating the CFD simulations of multi-dimensional laminar and turbulent reactive flows in the OpenFOAM framework. Starting from an introduction about the operator-splitting method, we discuss the relevance of ODE solvers for the integration of the chemical step and their links with the specific features of a detailed kinetic mechanism. Then, we proceed by introducing the SPARC (Sample-Partitioning Adaptive Reduced Chemistry) technique, a novel adaptive chemistry methodology for mitigating the computational costs of reactive-flows simulations, based on machine-learning algorithms which automatically classify the composition space via a priori defined classifiers. Finally, we present P(CA)2, a new method for Cell Agglomeration (CA), based on Principal Component Analysis (PCA), which automatically follow the temporal evolution of the thermo-chemical state of the system, identifying the most relevant species to be used in the CA process.
To better show the potential benefits and limitations of the proposed acceleration techniques, several examples will be presented and discussed: laminar coflow and counterflow diffusion flames, temporally-evolving planar jet-flames, heterogeneous catalytic reactors, etc.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-01-19T10:00:00Z'
date_end: '2023-01-19T11:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-01-20T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/CuociAlberto
url_code: ''
url_pdf: ''
url_slides: ''
url_video: https://www.youtube.com/watch?v=-k41aB1DdZY&t=344s&ab_channel=OpenFOAM%26CombustionSimulationWebinar

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - acceleration
---

# {{% callout note %}}
# Click on the **Slides** button above to view the built-in slides feature.
# {{% /callout %}}

# Slides can be added in a few ways:

# - **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
# - **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
# - **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

# Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.

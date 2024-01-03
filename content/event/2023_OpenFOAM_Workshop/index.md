---
title: Numerical simulations of reacting flows with detailed kinetic mechanisms in OpenFOAM

event: The First International OpenFOAM Combustion Workshop
event_url: https://blog.nus.edu.sg/huangwei/of4combust/

location: Chongqing, China
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: Numerical simulations of reacting flows with detailed kinetic mechanisms in OpenFOAM
abstract: 'The numerical modeling of multi-dimensional reactive flows with detailed kinetic mechanisms (including hundreds of species and thousands of reactions) places severe demands on computational resources, because of the number of strongly coupled equations involved and their high non-linearity and stiffness. 
This talk presents and discusses some numerical techniques for accelerating the simulations of multi-dimensional laminar and turbulent reactive flows in the OpenFOAM framework, with special emphasis on combustion. Starting from an introduction about the operator-splitting method, the connections between the features of detailed kinetic mechanisms and the ODE solvers for solving the chemical step will be analyzed. Then, the focus will be shifted on novel adaptive chemistry methodologies, like SPARC (Sample-Partitioning Adaptive Reduced Chemistry), based on machine-learning algorithms which automatically classify the composition space via a priori defined classifiers. Finally, Cell Agglomeration (CA) algorithms, combined Principal Component Analysis (PCA), like in P(CA)2, or with tabulated chemistry, will be presented as a further step to mitigate the computational cost associated to detailed kinetic mechanisms.
To better show the potential benefits and limitations of the described acceleration techniques, several examples will be presented and discussed: laminar coflow flames, temporally-evolving planar jet-flames, turbulent non-premixed flames in decaying isotropic turbulence, etc.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-06-19T09:25:00Z'
date_end: '2023-06-19T10:05:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-07-03T00:00:00Z'

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
url_video: https://www.youtube.com/watch?v=Ctz7ta8Wmb0&ab_channel=OpenFOAM%26CombustionSimulationWebinar

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
slides: ""

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

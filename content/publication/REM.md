+++
title = "A network scale, intermediate complexity model for simulating channel evolution over years to decades"
date = 2018-06-30T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Roderick W. Lammers", "Brian P. Bledsoe"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In Review with *Journal of Hydrology*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Excessive river erosion and sedimentation threatens critical infrastructure, degrades aquatic habitat, and impairs water quality. Tools for predicting the magnitude of erosion, sedimentation, and channel evolution processes are needed for effective mitigation and management. We present a new numerical model that simulates coupled river bed and bank erosion at the watershed scale. The model uses modified versions of Bagnold's sediment transport equation to simulate bed erosion and aggradation, as well as a simplified Bank Stability and Toe Erosion Model (BSTEM) to simulate bank erosion processes. The model is mechanistic and intermediate complexity, accounting for the dominant channel evolution processes while limiting data requirements. We apply the model to a generic test case of channel network response following a disturbance and the results match physical understanding of channel evolution. The model was also tested on two field data sets: below Parker Dam on the lower Colorado River and the North Fork Toutle River (NFTR) which responded dramatically to the 1980 eruption of Mount St. Helens. It accurately predicts observed channel incision and bed material coarsening on the Colorado River, as well as observations for the upstream 18 km of the NFTR watershed. The model does not include algorithms for extensive lateral migration and avulsions and therefore did not perform well in the lower NFTR where the channel migrated across a wide valley bottom. REM is parsimonious and useful for simulating network scale channel change in single thread systems responding to disturbance."
abstract_short = "Excessive river erosion and sedimentation threatens critical infrastructure, degrades aquatic habitat, and impairs water quality. Tools for predicting the magnitude of erosion, sedimentation, and channel evolution processes are needed for effective mitigation and management. We present a new numerical model that simulates coupled river bed and bank erosion at the watershed scale."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "pdf/Lammers_REM Paper 2018"
url_preprint = "https://eartharxiv.org/zgekr/"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "View Publication", url = ""}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/REM_schematic.png"
caption = ""

+++
### What we did and why it is important

Rivers are constantly changing. This is a natural process but often human intervention can accelerate river erosion and cause a wide array of issues from degraded water quality to destroyed bridges and roads. These problems are widespread but it is often unclear how best to mitigate their effects. Stabilizing a short section of stream might save a bridge, but rivers are networks and this stabilization could have unintended consequences downstream. 

We developed a model (the River Erosion Model, REM) that can be used to simulate channel change at the river network scale. The model simulates the *processes* that are important for predicting river movement (sediment transport and bank erosion) and can be used to understand how the whole river network will evolve in the future. There are a number of models for simulating river change; however, many are either very simple and are used at geologic time scales (i.e. millions of years) or very detailed but require so much data they are difficult to apply at the river network scale. REM, on the other hand, includes important processes but requires fewer data inputs --- making it easier to apply across entire watersheds.

An exciting potential application of REM is to test different erosion mitigation strategies (e.g. stabilizing a section of stream or reducing high flows) to determine their potential impacts on the stream system. This could be useful to determining the most cost-effective and sustainable approach to managing excessive erosion in rivers.

REM model code and User Guide can be found [here](https://github.com/rodlammers/REM)


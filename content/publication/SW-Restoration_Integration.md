+++
title = "Integrating stormwater management and stream restoration strategies for greater water quality benefits"
date = 2019-08-23T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Roderick W. Lammers", "Tyler A. Dell", "Brian P. Bledsoe"]

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
publication = "*Journal of Environmental Quality*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Urbanization alters the delivery of water and sediment to receiving streams, often leading to channel erosion and enlargement, which increases loading of sediment and nutrients, degrades habitat, and harms sensitive biota. Stormwater control measures (SCMs) are constructed in an attempt to mitigate some of these effects. In addition, stream restoration practices such as bank stabilization are increasingly promoted as a means of improving water quality by reducing downstream sediment and pollutant loading. Each unique combination of SCMs and stream restoration practices results in a novel hydrologic regime and set of geomorphic characteristics that interact to determine stream condition, but in practice, implementation is rarely coordinated due to funding and other constraints. In this study, we examine links between watershed-scale implementation of SCMs and stream restoration in Big Dry Creek, a suburban watershed in the Front Range of northern Colorado. We combine continuous hydrologic model simulations of watershed-scale response to SCM design scenarios with channel evolution modeling to examine interactions between stormwater management and stream restoration strategies for reducing loading of sediment and adsorbed phosphorus from channel erosion. Modeling results indicate that integrated design of SCMs and stream restoration interventions can result in synergistic reductions in pollutant loading. Not only do piecemeal and disunited approaches to stormwater management and stream restoration miss these synergistic benefits, they make restoration projects more prone to failure, wasting valuable resources for pollutant reduction. We conclude with a set of recommendations for integrated planning of SCMs and stream restoration to simultaneously achieve water quality and channel protection goals."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "headers/SW_Restoration.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = ["REM_project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "View Publication", url = "https://dl.sciencesocieties.org/publications/jeq/abstracts/0/0/jeq2019.02.0084?access=0&view=article"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "/headers/SW_Restoration.png"
caption = "Examples of stormwater controls (rain gardens, left) and stream restoration (willow planting, right) simulated in this research."

+++

### What we did and why it is important

Urbanization changes the water cycle. More impervious surfaces (parking lots, roads, buildings) means less water soaks into the ground and instead runs off into stream channels. This increases stream flow rates, and can cause significant erosion. Not only does this erosion damage streams, impair habitat, and threaten bridges and other infrastructure, it can be a source of pollution ([sediment and phosphorus primarily] {{< ref "BDC_LC.md" >}}). Two options to prevent this stream channel erosion are stormwater management and stream restoration. Stormwater management attempts to "fix" the altered urban water cycle - increasing infiltration of rain into soils and reducing high, erosive stream flows. Stream restoration attacks the problem in the channels themselves, reshaping stream banks and using vegetation or rock to make the channel less prone to erosion. These are both common practices, but aren't currently well coordinated to protect urban stream channels.

We used computer modeling to explore how stormwater management and stream restoration could be best integrated to prevent stream erosion and improve water quality. We modeled the effects of stormwater management on urban hydrology (rainfall -> runoff -> stream flow), and then used a separate [model]{{< ref "REM.md" >}} to see how much erosion and pollution was caused by these stream flows, and how well stream restoration worked. In general, we found that stormwater controls had a larger benefit than restoration. Stormwater approaches address the root cause of the problem (altered urban hydrology), while stream restoration only targets the symptom (channel erosion). However, when we coordinated both stormwater controls and stream restoration, we saw the biggest benefits for stream stability and water quality. This suggests that integrated planning of these projects is the best approach for urban stream management.

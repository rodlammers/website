+++
title = "Targeted hydrologic model calibration to improve prediction of ecologically-relevant flow metrics"
date = 2019-03-27T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sarah R. Parker", "Stephen K. Adams", "Roderick W. Lammers", "Eric D. Stein", "Brian P. Bledsoe"]

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
publication = "In *Journal of Hydrology*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "River flows exert dominant controls on in-stream biota. Quantifying linkages between hydrology and biology is important for assessing the effects of flow alteration on ecological functions. Hydrologic models are often used to quantify these flow-ecology relationships and guide management actions. Traditional model calibration techniques typically focus on a best overall fit criterion that may not be suitable for environmental flow applications where certain elements of the flow regime exert a dominant influence on biotic composition. We present an approach for hydrologic model calibration that improves the accuracy of calculated flow metrics known to be significant drivers of ecosystem response. First, we developed regional flow-ecology relationships based on streamflow gage and benthic macroinvertebrate data from southern California to determine which streamflow metrics best explain variability in taxonomic and trait-based biotic indices. Next, we developed and calibrated a series of hydrologic models to minimize error in these important flow metrics. For our study sites, flow flashiness and low flow frequency (indicative of drying) were found to best explain biotic condition. Hydrologic models calibrated specifically to minimize errors in these flow metrics predicted macroinvertebrate indices better than models calibrated to maximize fit to the overall flow regime. This ecological-calibration approach requires some a priori knowledge of flow-ecology relationships, but it produces results that can improve assessment of the impacts of changing flow regimes on biota and guide the development of strategies to mitigate ecological degradation."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

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
url_pdf = "pdf/Parker et al_Ecological flow calibration 2019.pdf"
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
#url_custom = [{name = "View Publication", url = ""}]
url_custom = [{name = "View Publication", url = "https://www.sciencedirect.com/science/article/pii/S0022169419303105"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/macroinvertebrate.jpg"
caption = "By RaquelGH1975 [CC BY-SA 4.0], via Wikimedia Commons"

+++
### What we did and why it is important

Rivers and streams are incredibly biologically rich. The plants, insects, fish, and other organisms that live in these freshwater ecosystems are constantly adjusting to one major driving force: river flow rates. Flow rates control water depth, velocity, and temperature, all important factors for aquatic organisms. The timing, magnitude, frequency, duration, and rate of change of high and low river flows are therefore vitally important for the integrity of these freshwater ecosystems; and understanding these flow "regimes" is also important for our understanding of stream biology.

Traditional "environmental flow analyses" use computer models to simulate hydrologic processes - rainfall, evaporation, infiltration, and runoff - to predict what river flows will look like under various conditions. These computer models must first be calibrated to match actual observed flow rates, and ensure they are accurately representing the real world. Often, these models are calibrated to best predict large flows, regardless of whether these are the most important flows for the organisms in the river.

We took a different approach. First, we used data on stream insects (benthic macroinvertebrates) and measured river flows to determine what parts of the flow regime the bugs most cared about (Sarah Parker did this work). In our southern California study area, these bugs were most concerned with how frequently flows got really low, and how quickly flow rates changed. We then used this information to calibrate hydrologic models that could accurately predict these specific flow metrics (Stephen Adams did this work). It turns out that these "ecologically-calibrated" models produced results that were more relevant for the stream biology than more traditional model calibration approaches. This new calibration approach could be useful for a wide range of environnmental flow applications, enabling us to better understand how changes in river flow rates affect the organisms that live there.

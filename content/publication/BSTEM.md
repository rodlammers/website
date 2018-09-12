+++
title = "Uncertainty and sensitivity in a bank stability model: Implications for estimating phosphorus loading"
date = 2017-03-30T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Roderick W. Lammers", "Brian P. Bledsoe", "Eddy J. Langendoen"]

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
publication = "In *Earth Surface Processes and Landforms*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Eutrophication of aquatic ecosystems is one of the most pressing water quality concerns in the United States and around the world. Bank erosion has been largely overlooked as a source of nutrient loading, despite field studies demonstrating that this source can account for the majority of the total phosphorus load in a watershed. Substantial effort has been made to develop mechanistic models to predict bank erosion and instability in stream systems; however, these models do not account for inherent natural variability in input values. To quantify the impacts of this omission, uncertainty and sensitivity analyses were performed on the Bank Stability and Toe Erosion Model (BSTEM), a mechanistic model developed by the US Department of Agriculture – Agricultural Research Service (USDA-ARS) that simulates both mass wasting and fluvial erosion of streambanks. Generally, bank height, soil cohesion, and plant species were found to be most influential in determining stability of clay (cohesive) banks. In addition to these three inputs, groundwater elevation, stream stage, and bank angle were also identified as important in sand (non-cohesive) banks. Slope and bank height are the dominant variables in fluvial erosion modeling, while erodibility and critical shear stress had low sensitivity indices; however, these indices do not reflect the importance of critical shear stress in determining the timing of erosion events. These results identify important variables that should be the focus of data collection efforts while also indicating which less influential variables may be set to assumed values. In addition, a probabilistic Monte-Carlo modeling approach was applied to data from a watershed-scale sediment and phosphorus loading study on the Missisquoi River, Vermont to quantify uncertainty associated with these published results. While our estimates aligned well with previous deterministic modeling results, the uncertainty associated with these predictions suggests that they should be considered order of magnitude estimates only."
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
url_pdf = "pdf/Lammers_BSTEM ESPL 2017.pdf"
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
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "/headers/BDC_bank.jpg"
caption = "An eroding streambank"

+++
### What we did and why it is important

Erosion of river banks is a natural process, but often human actions can accelerate this erosion --- turning this natural process into a problem. Bank erosion contributes soil (and pollution attached to the soil) into rivers and sends it downstream. This can pollute drinking water, make rivers and lakes unsafe for swimming, and kill fish and other aquatic life. It is important for water managers to understand how big of a problem bank erosion is, but measuring and monitoring erosion over large areas is difficult and expensive. Often, people use computer models to simulate erosion and determine if they need to invest in erosion protection measures. One commonly used model is the Bank Stability and Toe Erosion Model (BSTEM) developed by the US Department of Agriculture (erosion of streams around farms is a common issue).

While this model is useful for understanding bank erosion processes, it still requires certain inputs that can be difficult to estimate (for example, how resistant is the bank soil to erosion). In addition, these model inputs are often not constant everywhere; in fact, many soil characteristics can vary significantly even across a few hundred feet of streambank. To help model users apply BSTEM, we conducted an uncertainty and sensitivity analysis of the model. Uncertainty analysis involves running the model thousands of times, varying the input variables across reasonable ranges of values. This gives a *distribution* of model outputs, as opposed to a single model result from a single model run. This is useful for determining how confident users can be in model outputs. Sensitivity analysis takes the output from the uncertainty analysis and determines which specific model inputs contribute most to model uncertainty. These "most important" model inputs have the biggest effect on model results, so it is important to accurately measure these values.

For BSTEM, we found that soil cohesion (i.e. how "sticky" or clayey the soil is) has the biggest effect on modeling bank collapse. For bank erosion, the soil resistance was suprisingly not found to be that important using our sensitivity analysis methods; however, it is likely this soil resistance is more important than we showed because it controls both the rate and *timing* of bank erosion. Bank height and channel slope were also important model inputs. This is useful to model users because they can focus their data collection efforts on these few, important model inputs and worry less about measuring the other, less influential parameters.

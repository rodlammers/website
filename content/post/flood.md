+++
title = "A flood by any other name..."

date = 2016-05-10T00:00:00
lastmod = 2016-05-10T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = ["floods"]
summary = "How we talk about floods impacts our understaning of the risks they pose."

[header]
image = "headers/Flood.jpg"
caption = "Image credit: NASA [Public Domain] via Wikimedia Commons"

# Does this page contain LaTeX math? (true/false)
math = true
+++

What is a flood? It seems like a silly question but it’s sometimes useful to define things that seem like common sense. According to the [1968 National Flood Insurance Act](https://www.fema.gov/media-library-data/20130726-1748-25045-5315/floodact.pdf#page=86), a flood is “inundation from rising waters or from the overflow of streams, rivers, or other bodies of water.” You’ll notice that at no point in the definition is there any mention of damage associated with this rising water. Hydrologists tend to define floods as anytime the flow in a river spills out of the channel and the water goes over the banks. The fact is, floods are common events that are a natural part of the hydrologic cycle. It is a general rule of thumb in hydrology that flow in a river goes over the bank about once every 1.5 – 2 years. This, like everything in nature, is highly variable. For example, there are some rivers in the coastal region of the southeastern U.S. where water is overbank for the majority of the year, every year. On the other hand, some desert streams may only fill up their channel once every 10 or 20 years. The point is that flooding cannot be considered an infrequent event. In fact, floods are essential for proper ecological function. Overbank flows deliver nutrient-rich soil to floodplains (why do you think they are so popular for farming) and provide important habitat for fish and other plant and animal species.

If floods are so common and have so many important environmental benefits, why are they so often viewed as natural disasters? A flood becomes a disaster only when human development gets in the way of the rising water. Unfortunately, this happens frequently because waterfront property is so popular. To address this issue of continued flood damage in these floodplain properties, the U.S. government formed the National Flood Insurance Program (NFIP) to provide these homeowners some financial security. This program requires people within the “100-year” floodplain to purchase flood insurance (often at discounted rates). Most people have heard of the “100-year” flood, but many don’t have a good understanding of what it means. Contrary to what may be intuitive, a “100-year” flood does not happen once every 100 years. Instead, it is the flood that has a 1% chance of happening in any given year. There is no reason two “100-year” floods couldn’t occur in back-to-back years. Put another way, a “100-year” flood has a 26% chance of occurring over a 30-year mortgage (this oddly specific value is simply the nature of probability – compounding a 1% chance of occurrence over 30 years)[^1]. Using these different terms to talk about the same event can significantly influence perception of risk associated with a flood.

So how do we figure out the size of this “100-year” flood? The most common way is to use historic river flow records to estimate the frequencies of flows of different magnitudes. Unfortunately, it is pretty rare to have a 100-year record of river flow at any point, so we are often forced to use a probability function to predict what the magnitude of this “100-year” flow will be. This function introduces some uncertainty into this analysis which means we can’t be entirely confident in our estimates for the “100-year” flood. Using example data from the White River in Indianapolis (near where I grew up), I’ve illustrate how this analysis is done (see figure below). The solid line is the fitted probability function while the red shading indicates uncertainty around this function. This uncertainty creates a large range of potential flow sizes for the “100-year” flood. Also note the largest flood on record doesn’t fit the observed trend. Issues like this make flood prediction very difficult.

![img](/img/Flood_Plot.png)

Another source of error is that fact that we are using historical flow records to predict the probability of future events. This assumes that these historic floods are representative of future conditions which is almost never the case. Development in the floodplain and outside of it alters the natural hydrology of an area. Increasing “impervious area” (e.g. buildings, roads, or other surfaces that don’t allow water to soak into the ground) leads to greater river flows, even for the same amount of precipitation. In addition, levees may (and I emphasize “may”) prevent flood damage at a single site but they tend to increase downstream flood risk by keeping more water in the channel instead of allowing it to dissipate naturally on floodplains. Because these changes are often ongoing in a watershed, the magnitude of the "100-year" flood must be recalculated through time as new flow data become available.

So what is a flood? Terms and definitions of floods often mean different things to different people. This variable terminology can lead to confusion and uncertainty about the probability of large flood events and the risks they pose to floodplain residents. Floods are common but unpredictable events and communicating effectively about the risks they pose requires consistent understanding of what we truly mean when we use the word "flood."

[^1]: For those of you who want more specifics, this cumulative flood risk over time is calculated using the following equation: Risk = $1 – (1 – p)^N$ where $p$ is the probability (1% in this case) and $N$ is the number of years (30).
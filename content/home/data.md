+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Data"


# Order that this section will appear in.
weight = 50

#One way we could make this different is to present the places of teaching as a smaller list with a click through to course descriptions and why we were teaching at that location. More in line with the project presentation line of reasoning. If we did each teaching engagement independently like a talk, and then aggregate them, then we could use schema.org metadata to describe each teaching engagement.

+++
<h2>Corruption</h2>

_My dissertation draws on an original database of approximately 120,000 criminal corruption cases in China from 2001 to 2023. It covers all major corruption offenses under Chinese criminal law: bribe-taking, bribe-giving, embezzlement, misappropriation of public funds, and abuse of power. To extract structured information from these semi-structured legal documents, I developed a Large Language Model-based extraction pipeline that parses all cases into (1) more than 380,000 individual corrupt events with their corruption dates, amounts, types, and related firms, and (2) 120,000 case-level data on defendant information including demographics, position, and sentence outcomes. I link these data to anti-corruption inspections and firm-level government procurement database. To my knowledge, this is the most comprehensive transaction-level corruption dataset assembled for any single country._

<h2>Round-tripping FDI</h2>

_Round-trip foreign direct investment—domestic capital that exits a country through offshore financial centers and returns disguised as foreign investment—poses significant measurement challenges for understanding the politics and economics of FDI. This dataset identifies round-trip FDI at the firm level in China using machine learning classification applied to the Foreign-Invested Enterprises in China (FIEC) database. We hand-coded ultimate beneficial ownership for a training sample of 3,300+ firms across Beijing, Nanjing, and Taiyuan, tracing ownership chains through corporate registries and commercial databases to distinguish genuinely foreign investors from mainland-controlled entities using offshore structures. Using these validated labels, we trained a random forest classifier on firm characteristics including ownership structure, registered capital, state involvement, and sector to predict round-trip status for the full population of foreign-invested enterprises. The resulting predictions enable classification of round-trip status for 25,000+ foreign-invested enterprises across three major cities from 2017-2023. This dataset enables researchers to distinguish round-trip from genuinely foreign capital in firm-level analyses of FDI behavior, policy responses, and economic outcomes in China._


---
title: Project Summary
id: home
description: "At risk butterflies: phenology and abundance in the United States"
layout: storymap
---

<img src="/assets/images/SERDP Multispecies Collage.png" alt="Species Collage of butterflies" width="90%">

## Introduction

We worked with butterfly researchers and naturalists across the United States to find datasets that allowed us to evalute the phenology, or the timing of flight periods, and abundance of butterflies that are of conservation concern.

Scientists have hypothesized that species that get earlier are declining and species that get later are increasing. Species with longer flight periods would be increasing and species with shorter flight periods would be decreasing.

For at-risk butterflies we ask if phenological shifts, and the abundance are correlated.

## Methods and Definitions

We first idenitified what species are considered at-risk, with help from Candance Fallon at Xerces Society for Invertebrate Conservation, we called species at-risk in a given state if: they are listed federally or within that state, if the state's wildlife agency has reported them as a Species of Greatest Conservation need, or if they are considered to have a vulnerable or more at-risk listing on NatureServe.org. We have many butterflies which are federally listed at the subspecies level which precludes some conservation status assessment lists.

Next, we gathered long-term data for as many species as possible. Sufficient data was at least ten years of survery, with multiple surveys within a year. We gathered community datasets, which survey for many butterfly species simultaneously in the same locaiton, and single-species datasets, which has surveys designed for a species of interest. Ocassionally, there are datasets that begin as one type and move to another.

Two types of data were excluded from analysis. Data from sub-tropical regions because they do not experience phenology in the same manner as temperate species, and species not within the continental United States. We also excluded particular years within datasets where captive rearing and release was occuring, which sometimes led to excluding a site altogether. Captive rearing and release includes individuals that are not subject to the same environmental conditions and could modify the population phenology.

For analysis we formed separate smoothing splines for each site of each species, smoothing across the day of year, and treating year as a continuous variable. For some datasets that did not capture a survey prior to or after the flight period (surveys with zeros) estimates of butterfly activity became problematic. To solve this we used artificial zeros two weeks on either side of the last survey. Very low years with many zero counts were not used to estimate phenology, and some data with very few positive counts were not used to estimate the butterfly activity index.


## Results
Overall we found that there are no correlations between phenological shifts and changes in abundance over time across these at-risk butterflies from five families and across 10 states. Many spring species are advancing at some of their sites, and many late summer species are delaying.

<iframe height="500" width="100%" frameborder="no" src="https://kking.shinyapps.io/Multispecies/"> </iframe>

We do not find that results are spatiallly correlated, with trends in species abundance or phenoloy being similar in closer locations.

<iframe src="https://wsuniv.maps.arcgis.com/apps/instant/basic/index.html?appid=e3ccf346c38d47e6b901cded95474c77" width="450" height="450" frameborder="0" style="border:0" allowfullscreen> </iframe>

We also found that datasets that target specific species were much more able to contribute meaningful data, over datasets that survey many butterfly species, or community datasets. Our data do not cover many areas of the United States which may be strongly affected by climate change. For example, there are only a few species in higher elevation mountain sites. The lack of data we have for these areas is partially logistical, as surveys in some terrain is not accessible for people, but it is for butterflies.

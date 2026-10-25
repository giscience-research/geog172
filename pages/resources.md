---
layout: page
title: Resources
---

## Lecture and Activity Summaries

Activity summaries provide very brief overviews of the key concepts and lessons covered in each week's lectures and activities. The slides are posted along. These materials serve as reminders, not substitutes for participating in the activities or attending the lectures themselves.

<details>
<summary><strong>&nbsp; Week 0 - Mapping Our Geographic Experience</strong></summary>

The activity for Week 0 is centered around building a collective map of geographic experience across the classroom. Through the placement of points for places students know well and places they hope to visit, we begin to see how familiarity, travel, and social context shape the spatial distribution of knowledge. The exercise highlights how a simple map can reveal spatial patterns, how those patterns can be interpreted as evidence of underlying processes, and how geographic experience influences the data we generate. The key takeaway is that observation and explanation are distinct: a map shows a pattern, but understanding why that pattern exists requires careful attention to the processes and people behind it.

<br>
<a href="../slides/WK0-Introduction.pdf">Lecture Slides - Introduction</a>

</details>

<br>

<details>
<summary><strong>&nbsp; Week 1 - Pin It to Win It & The Cancer Map Mystery</strong></summary>

This week's activities introduce spatial data as observations tied to locations and shaped by the data-generating process. In <em>Pin It to Win It</em>, students use visual geographic clues to estimate locations on a U.S. map, showing how different prior knowledge and uncertainty can produce different spatial observations from the same information. In <em>The Cancer Map Mystery</em>, they compare maps of high and low kidney cancer rates and test whether striking geographic patterns can arise from random variation when population sizes differ. The central lesson is that a map reveals a pattern, but understanding that pattern requires asking how the data were produced, what denominator was used, and whether chance or measurement choices are driving the apparent structure.

<br>
<a href="../slides/WK1-SpatialData.pdf">Lecture Slides - Spatial Data</a>

</details>

<br>

<details>
<summary><strong>&nbsp; Week 2 - The Center Hunter</strong></summary>

This week's activity introduces centrography by asking students to summarize the spatial patterns they created during the Week 1 GeoGuessr exercise. In the first exercise, <em>The Center Hunter</em>, students calculate the mean center of the class's guesses for Meredith, New Hampshire by averaging the x- and y-coordinates separately, then compare the calculated center with their visual estimate and consider the influence of an outlier. In the second exercise, they calculate a weighted mean center for guesses about Minneapolis, Minnesota, using the population of each guess's state as the weight. Comparing the unweighted and weighted centers shows how an attribute can change the question a spatial summary answers: more populous states exert greater influence, shifting the center toward observations with larger weights. The central lesson is that a center is a concise description of a spatial distribution, not a complete representation of its pattern, and that weighting changes the meaning of that description.

<br>
<a href="../slides/WK2-C1-Centrography.pdf">Lecture Slides - Centrography</a>
<br>
<a href="../slides/WK2-C2-SpatialInequality.pdf">Lecture Slides - Spatial Inequality</a>
</details>


<br>
<details>

<summary><strong>&nbsp; Week 3 - The Random Orchard Challenge & Spatial Clues in the New England Woods</strong></summary>

This week's activities introduce the absence of independence and the different processes that can shape spatial variation. In <em>The Random Orchard Challenge</em>, students try to plant 30 fruit trees randomly within a rectangular plot, then inspect another group's orchard by scoring the concentration of trees across a grid. They compare their scores with a distribution generated from many computer-simulated random orchards and discover that random patterns can contain clusters, gaps, and uneven spacing. The activity highlights how people often produce or interpret regularity when they try to create randomness, and it motivates the use of spatial statistics when observations are not independent.

In <em>Spatial Clues in the New England Woods</em>, students work in pairs to classify excerpts about the forest landscape as examples of first-order variation, second-order variation, directional variation, or insufficient evidence. The clues illustrate how spatial patterns may be driven by local environmental conditions, interactions among nearby trees and landscape features, or processes with a directional tendency. Together, the activities emphasize that spatial patterns reflect data-generating processes and that identifying those processes is essential for choosing and interpreting spatial statistical methods.

<br>
<a href="../slides/Wk3-C1-Random.pdf">Lecture Slides - Randomness and Spatial Effects</a>
<br>
<a href="../slides/Wk3-C2-Sampling.pdf">Lecture Slides - Spatial Sampling</a>

</details>


<br>

<details>
<summary><strong>&nbsp; Week 4 - The Random Orchard Audit</strong></summary>

This week's activity revisits the Random Orchard using a separation-based approach to point-pattern analysis. Working as auditors, students identify the nearest neighbor for each of ten focal plants, calculate the observed mean nearest-neighbor distance, and compare it with the expected distance under complete spatial randomness. They use the resulting nearest-neighbor index to assess whether each orchard is clustered, dispersed, or consistent with random planting. Students then repeat the audit with a guard area surrounding the original orchard to investigate edge effects, examining how an artificial study boundary can make nearest-neighbor distances appear larger when nearby plants outside the boundary are not observed. The central lesson is that different spatial statistics describe different characteristics of the same point pattern: quadrat methods measure concentration across areas, while nearest-neighbor analysis measures separation among observations, and both depend on careful analytical design.

<br>
<a href="../slides/WK4-C1-PointPatterns.pdf">Lecture Slides - Describe Point Patterns</a>
<br>
<a href="../slides/WK4-C2-AssessPointPatterns.pdf">Lecture Slides - Assess Point Patterns</a>
</details>


<br>

<br>

## Statistical Demonstrations

A series of computational notebooks presenting geographic concepts and spatial statistics with R code demonstrating their implementation. These materials draw extensively from *Spatial Statistics for Geography* and *Geographic Information Analysis*.

| Week | Demonstration |
| --- | --- |
| 0 | --- |
| 1 | [Learning the Data Generating Process](../demo/WK1-DGP.html) |
| 2 | [Locating the Center of the U.S. Population](../demo/WK2-Centrography.html) <br> [Drawing the U.S. Hu Line](../demo/WK2-HuLine.html) |
| 3 | [Spatial Data Generating Processes](../demo/WK3-Spatial-Process.html) <br> [Spatial Sampling Schemes](../demo/WK3-Sampling.html) |
| 4 | [Point Pattern Analysis](../demo/WK4-Point-Pattern.html) |
| 5 | [Understanding Modifiable Area Unit Problem](../demo/WK5-MAUP.html) |
| 6 | [Global Statistics](../demo/WK6-Global.html)<br> [Moran's I Calculation](../demo/Morans-I-by-Hand.pdf) |
| 7 | [Local Statistics](../demo/WK7-Local.html) |
| 8 | [Impacted Inference](../demo/WK8-Inference.html) |
| 9 | TBD |
| 10 | TBD |

Demonstration of selected statistics in alternative software (e.g., ArcPro, GeoDa) are available on the canvas website for this course.

## Independent Online Resources

Two resources for installing R and RStudio and getting started with R:

- [ModernDive, Chapter 1: Getting Started with Data in R](https://moderndive.com/v2/01-getting-started.html)
- [swirl](https://swirlstats.com/students.html): An interactive way to learn R in the R console.

[R For Data Science 2e](https://r4ds.hadley.nz/): Free web version of book in R Series. Introduces R and the tidyverse.

[Statistical Learning with R](https://www.stat.berkeley.edu/users/rabbee/s154/ISLR_First_Printing.pdf): Free online version of the book. Covers statistical learning methods with R.

[Geocomputation with R](https://geocompr.robinlovelace.net): Free web version of book in R Series. Contains details on manipulating spatial data in R.

[R Graph Gallery](https://r-graph-gallery.com/index.html): Collection of R chart examples with code. Includes a curated collection of ‘best of’ examples use for inspiration.

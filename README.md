# R Mini Bootcamp: Beginner-level Focus

A beginner-friendly introduction to R programming. No prior coding experience needed.

**Author:** Jake Leighton, PhD — Department of Translational Molecular Pathology,
MD Anderson Cancer Center

## What's covered

**Part 1: R Fundamentals and Data Structures** (RStudio, packages, data types,
vectors, lists, matrices, data frames, built-in datasets)

**Part 2: Data Import and Manipulation** (reading/writing files, missing data,
base R subsetting, tidyverse/dplyr verbs, the pipe, grouping, data cleaning, joins)

Examples use R's built-in `ChickWeight` and `DNase` datasets, so there's nothing extra to download.

## Materials

| | View online | Download Rmd |
|---|---|---|
| **Main Lesson** | [Open lesson](https://jakesleighton.github.io/intro-r-basics/R_MiniBootcamp_Workshop_JL.html) | [R_Bootcamp_Beginner_Workshop_JL.Rmd](https://github.com/jakesleighton/intro-r-basics/raw/main/R_Bootcamp_Beginner_Workshop_JL.Rmd) |
| **Practice Assignment (Solutions)** | [Open practice](https://jakesleighton.github.io/intro-r-basics/R_MiniBootcamp_Workshop_Practice_JL.html) | [R_Bootcamp_Beginner_Workshop_Practice_JL.Rmd](https://github.com/jakesleighton/intro-r-basics/raw/main/R_Bootcamp_Beginner_Workshop_Practice_JL.Rmd) |

**Suggested order:** Work through the main lesson first. Try the Practice
Assignment at the end of the lesson on your own, then check your work against
the Practice Solutions.

## Run it yourself

1. Install [R](https://cran.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/).
2. Download the `.Rmd` files using the links above.
3. In RStudio, install the packages once:
   ```r
   install.packages(c("tidyverse", "patchwork"))
   ```
4. Open the `.Rmd`, then run the chunks one at a time or click **Knit** to build the HTML.

## About

This bootcamp is an early piece of a larger computational training curriculum
covering R programming, statistics, machine learning, and cancer genomics
(RNA, DNA, copy number). The full curriculum will be released publicly soon.

Questions or interest in the full program? Contact Jake Leighton.

## License

© 2026 Jake Leighton. Free to use for teaching and learning with attribution.
Not for commercial use without permission.

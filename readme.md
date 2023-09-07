# Center for Health Journalism: Data Fellowship 2023

------------------------------------------------------------------------

Christian McDonald [?\@ut.edu](mailto:?@ut.edu){.email}
Andrew Ba Tran [andrew.tran\@washpost.com]{.email}

## Getting Started

Learning to code with a language like R takes some time and effort on your part. We'll be covering a lot of foundation material this week, and sometimes this can feel like a firehouse of obscure information (e.g. what is an atomic vector and how is that different from a list) that you don't know what to do with yet. If you feel that way, that's OK! You will most likely have to go back and look this stuff up again. But it will help you get started today as we start flexing those coding muscles.

You should expect to feel some frustration, because everybody does. Frustration is OK so long as you can persevere through it. When you finally solve the problem and your code works it's a GREAT feeling.

## Get the files

## Before we move on, run these lines in console

```
install.packages(c("usethis", "tidyverse", "remotes"))

remotes::install_github("r-journalism/chjr23", upgrade="always", quiet=TRUE)

usethis::use_course("https://github.com/r-journalism/chjr2323/archive/master.zip")
```


#### Resources
-   [Slideshow of R Basics](https://r-journalism.github.io/chjr23/01_intro_to_r_rstudio.html#/title-slide)
-   [Slideshow of Wrangling Data](https://r-journalism.github.io/chjr23/02_wrangling_data.html#/title-slide)
-   [Slideshow of Tidying data](https://r-journalism.github.io/chjr23/03_tidying_data.html)
-   [Slideshow of Vizualizing data](https://r-journalism.github.io/chjr23/04_visualizing_data.html)
-   [Tidyverse documentation](https://www.tidyverse.org/): We'll be referring back to this a lot. Get used to reading documentation; it's an important skill!
-   [data](data/): Some of the data we'll be using for this class is in the data folder of this repository
-   [practice scripts](practice/): There are exercises in the practice folder that you can work on your own time
-   [weird ggplots](https://docs.google.com/presentation/d/1KZooYWyeE0DtMmuD5hGGern0zqixIh49OC304UtYSkM/edit)
-   [ggplot2 code gallery](https://r-graph-gallery.com/ggplot2-package.html)

#### Practice
-   To practice creating and working with vectors and doing simple variable assignment, use [R-Basics.Rmd](practice/R-Basics.Rmd)
-   To practice importing and the basics of data analysis (sorting, filtering, aggregating), use [Importing-and-intro-to-data-analysis.Rmd](practice/Importing-and-intro-to-data-analysis.Rmd)

#### Day 1: Intro to R and RStudio


#### Day 2: Wrangling data


#### Day 3: Transforming data
- [Slides](https://r-journalism.github.io/chjr23/03_tidying_data.html)
- `learnr::run_tutorial("3_a_joining", "chjr23")`
- `learnr::run_tutorial("3_b_math_pivots", "chjr23")`

#### Day 4: Visualizing data
- [Slides](https://r-journalism.github.io/chjr23/04_visualizing_data.html)
- `learnr::run_tutorial("2_a_viz", "chjr23")`
- `learnr::run_tutorial("2_b_exploratory_viz", "chjr23")`


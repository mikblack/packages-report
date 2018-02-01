
<!-- README.md is generated from README.Rmd. Please edit that file -->
packages-report
===============

Workshop challenge checklist
----------------------------

*As you complete tasks, you can ~~cross them out~~ by surrounding with `~~`.*

-   ~~Have a look around the files here. Where are the R scripts? What are the directories `data` and `figs` for?~~
    -   R scripts live in the `R` directory
    -   `data` contains data files (csv)
    -   `figs` contain figures (png)
-   ~~Notice that this README is an `.Rmd` file. That means it could contain R code and will need to be rendered to create `README.md`.~~
    -   Yep, noticed that AFTER editing it. :)
-   ~~Open [R/01\_write-installed-packages.R](R/01_write-installed-packages.R). Write the script as directed. Run it. Commit and push the current state.~~
-   ~~Open [R/02\_wrangle-packages.R](R/02_wrangle-packages.R). Fill in the missing pieces of the script as directed. Run it. Commit and push the current state.~~
-   ~~Open [R/03\_barchart-packages-built.R](R/03_barchart-packages-built.R). Fill in the missing pieces of the script as directed. Run it. Commit and push the current state.~~
-   Fill in the blanks below in this README, using the results stored elsewhere.
-   If you get this far, write an R script to run the whole analysis and, perhaps, another script that does a `make clean` style reset.

Overview
--------

The goal of packages-report is to count the number of R packages installed on the user's system, that were built under each version of R.

I have `sum(apt_freqtable$n)` add-on packages installed.

Here's how they break down in terms of which version of R they were built under, which is related to how recently they were updated on CRAN.

| Built |    n|       prop|
|:------|----:|----------:|
| 3.3.2 |    6|  0.0128205|
| 3.4.0 |  165|  0.3525641|
| 3.4.1 |   38|  0.0811966|
| 3.4.2 |  107|  0.2286325|
| 3.4.3 |  152|  0.3247863|

![](figs/built-barchart.png)

### Flow of the analysis

*If you have time, document the analysis works, using internal links.*

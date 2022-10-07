# Workshop presentations

Please publish your presentation materials in a repo that you create in our workshop organization at https://github.com/intro-to-data-science-22-workshop. There's a naming convention for the repos, which should indicate the workshop number (see below), your name (one group member only), and a very brief description, all lowercase and separated by dashes. E.g.: `01-topic-lastname1-lastname2/`. For more information about your task, check out the document `workshop-guidelines.pdf` in this repository.

## R Markdown

Please try to make your presentations using [R Markdown](https://rmarkdown.rstudio.com/). You can use any one of the multiple slide deck options. (For what it's worth, I use the [xaringan package with a modified metropolis theme](https://github.com/yihui/xaringan/wiki/Themes) for my lecture slides). Or you can output as a [GitHub document](https://rmarkdown.rstudio.com/github_document_format.html) or [HTML document](https://bookdown.org/yihui/rmarkdown/html-document.html). If you choose the latter, I would request that you please include `keep_md: true` in your YAML, so that it is readable directly on GitHub.

## Recording

There are multiple ways to record your computer screen and voice for the presentation videos. You can [record MS PowerPoint with audio and video](https://www.youtube.com/watch?v=2m60HT3OMOI), [record a presentation on Zoom](https://www.youtube.com/watch?v=P6cTbnUPwfY), [record a presentation via MS Teams](https://www.youtube.com/watch?v=ymnTVklGtAY), or use [open source software OBS Studio](https://www.youtube.com/watch?v=jKgM18lOsr4). Just make sure the `format is mp4` and the entire thing is `no longer than 15 minutes`! If you need to convert between video formats, I recommend the open source video transcoder [HandBrake](https://handbrake.fr/). For minimal cutting you might want to use lightweight [LosslessCut](https://github.com/mifi/lossless-cut).


## Topics

Topics will be randomly allocated to groups of 2 students. Both of you should contribute to both the presentation and the practice session, but you can divide main responsibilities.

| Workshop | Focus | Topic | Resources | 
|---------|-------|-----------|-----------|
| 01 | Data wrangling | Creating web APIs with plumber | [a](https://www.rplumber.io/), [b](https://github.com/rstudio/cheatsheets/raw/master/plumber.pdf) |
| 02 | Data wrangling | Cleaning dirty data with janitor | [a](https://github.com/sfirke/janitor), [b](http://sfirke.github.io/janitor/articles/janitor.html) |
| 03 | Data wrangling | Categorical variables with forcats | [a](https://forcats.tidyverse.org/), [b](https://r4ds.had.co.nz/factors.html) |
| 04 | Data wrangling | Dates and times with lubridate | [a](https://lubridate.tidyverse.org/), [b](https://r4ds.had.co.nz/dates-and-times.html) |
| 05 | Data wrangling | Wrangling data at scale with data.table | [a](https://rdatatable.gitlab.io/data.table/), [b](https://github.com/tidyverse/dtplyr) |
| 06 | Data wrangling | String manipulation with stringr | [a](http://www.r-datacollection.com/), [b](https://github.com/rstudio/cheatsheets/raw/master/strings.pdf) |
| 07 | Visualization | Network graphs with ggraph and tidygraph | [a](https://ggraph.data-imaginist.com/), [b](https://tidygraph.data-imaginist.com/) |
| 08 | Visualization | Interactive maps with leaflet | [a](https://rstudio.github.io/leaflet/), [b](https://leafletjs.com/reference-1.7.1.html) |
| 09 | Visualization | Interactive graphics with plotly | [a](https://github.com/ropensci/plotly), [b](https://plotly.com/r/) |
| 10 | Data analysis | Text analysis with quanteda | [a](https://quanteda.io/), [b](https://joss.theoj.org/papers/10.21105/joss.00774) |
| 11 | Data analysis | Tidying text data with tidytext | [a](https://www.tidytextmining.com/), [b](https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html) |
| 12 | Data analysis | Coordinate reference systems with sf | [a](https://geocompr.robinlovelace.net/spatial-class.html#crs-intro), [b](https://r-spatial.github.io/sf/index.html) |
| 13 | Data analysis | Geocoding with sf | [a](https://r-spatial.github.io/sf/index.html), [b](https://lost-stats.github.io/Geo-Spatial/geocoding.html) |
| 14 | Data analysis | Temporal data with tsibble and fable | [a](https://tsibble.tidyverts.org/), [b](https://fable.tidyverts.org/) |
| 15 | Programming | Measuring and improving performance | [a](https://adv-r.hadley.nz/perf-measure.html), [b](https://adv-r.hadley.nz/perf-improve.html) |
| 16 | Programming | Parallel programming with future | [a](https://raw.githack.com/uo-ec607/lectures/master/12-parallel/12-parallel.html), [b](https://cran.r-project.org/web/packages/future/vignettes/future-1-overview.html) |
| 17 | Workflow | Ensuring reproducibility with renv | [a](https://rstudio.github.io/renv/), [b](https://rstudio.github.io/renv/articles/renv.html) |
| 18 | Workflow | Establishing pipelines with targets | [a](https://docs.ropensci.org/targets/), [b](https://books.ropensci.org/targets/) |
| 19 | Workflow | Creating R packages | [a](https://www.mzes.uni-mannheim.de/socialsciencedatalab/article/r-package/), [b](https://r-pkgs.org/) |
| 20 | Publication | Publishing with Quarto | [a](https://quarto.org/), [b](https://github.com/mcanouil/awesome-quarto) |
| 21 | Publication | Publishing websites with GitHub pages | [a](https://pages.github.com/), [b](https://docs.github.com/en/pages/quickstart) |




<!-- README.md is generated from README.Rmd. Please edit that file -->
Experimental Fork for:
======================

rrtools: Tools for Writing Reproducible Research in R
-----------------------------------------------------

For the production version of `rrtoolts` go to: <https://github.com/benmarwick/rrtools>

<!-- Project Template Example: -->
<!-- ![](https://raw.githubusercontent.com/mrecos/rrtools/master/Screenshot.png) -->
Project Template
----------------

The focus of this fork is to provide a simple template for the creation of a basic research compendium using the `rrtools` package. This approach takes advantage of the new *Project Template* option in RStudio Version 1.1.xxx. See [here](https://rstudio.github.io/rstudio-extensions/rstudio_project_templates.html) for some details of how it is implemented. What this branch provides is a way to use the new Project Template as a user interface to creating a basic research compendium. The basic compendium template includes the most common options of compendium setup including folder structure, Github, README, and MIT license. More advanced options such as using continuous integration (CI) will require a separate action once the package is created. Even is CI is desired, the basic project template can still be used for the initial package creation. This is an experimental use of the new package template framework and will surely have bugs. Please report those as Issues or Pull Requests and I will sort it out.

Usage
-----

### 1- Install this branch of `rrtools`

``` r
# install.packages("devtools")
devtools::install_github("mrecos/rrtools")
library("rrtools")
you may have to resart RStudio if this your first use.
```

### 2 - Create New Project

Note: The package name should contain only ASCII letters, numbers and dot, have at least two characters and start with a letter and not end in a dot. Otherwise, you will get an error telling you such. ![](https://raw.githubusercontent.com/mrecos/rrtools/master/analysis/images/1_new_dir.png)

### 3 - Select 'Create Reserch Compendium'

![](https://raw.githubusercontent.com/mrecos/rrtools/master/analysis/images/2_compendium.png)

### 4 - Select Options and Provide Info

To use GitHub you will need a GitHub account and [peronal API token](https://github.com/blog/1509-personal-api-tokens) ![](https://raw.githubusercontent.com/mrecos/rrtools/master/analysis/images/3_template_options.png)

### 5 - Accept Description Default (will fix this soon)

![](https://raw.githubusercontent.com/mrecos/rrtools/master/analysis/images/4_select1.png)

### 6 - Success!

![](https://raw.githubusercontent.com/mrecos/rrtools/master/analysis/images/5_GH_desc.png)

From this basic package setup, there are additional options that can be used, Description and README.Rmd to fill in. Check out the main branch of [rrtools](https://github.com/benmarwick/rrtools)for info.

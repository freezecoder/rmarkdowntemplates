# rmarkdowntemplates



## Introduction

These are boilerplate templates in Rmarkdown for generating quick reports.


## Installation

These work best when used in Rstudio. Install Rstudio and also install KnitrBootstrap [https://github.com/jimhester/knitrBootstrap]

```
library(devtools)
install_github('rstudio/rmarkdown')
install.packages('knitr', repos = c('http://rforge.net', 'http://cran.rstudio.org'),
                 type = 'source')
install_github('jimhester/knitrBootstrap')
```

## Usage

Clone this repo, edit the content and Knit using Rstudio's knit button or you can use the following commands


```
library(knitrBootstrap)
library(rmarkdown)
render('RegularReportTemplate.Rmd', 'knitrBootstrap::bootstrap_document')

```

## Examples

Download the HTML files in the examples/ folder and open them in your web browser.


 

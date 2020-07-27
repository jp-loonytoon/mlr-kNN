# kNN Examples

Examples that use mlr to perform k-Nearest Neighbour predictions on common data sets.

## Overview
This project uses the `mlr` and `mlr3` packages to run kNN analysis on several datasets.

## Usage
Run the various R notebooks. You can do this from within RStudio, or using the following commands:

```r
library(rmarkdown)
render("diabetes-knn-mlr.Rmd", html_document())
```

### Using Jupyter Notebooks
If you use Jupyter rather than RStudio you should be able to still view the .Rmd file as R notebooks represented in the R Markdown (Rmd) format can run both in Jupyter and RStudio. In case you want to manually create an .ipynb notebook file you can use install and run the `jupytext` utility as follows:

```bash
jupytext --update-metadata '{"kernelspec": {"display_name": "R", "language": "R", "name": "ir"}}' --to notebook diabetes-knn-mlr.Rmd
```

See the [Jupytext](https://github.com/mwouts/jupytext) project for more examples.

The [I2ML](https://github.com/compstat-lmu/lecture_i2ml) course is really helpful to get started with mlr, as well as the book [_Machine Learning with R, the tidyverse, and mlr_](https://www.manning.com/books/machine-learning-with-r-the-tidyverse-and-mlr) by Hefin Rhys. For more info on the mlr package see: https://mlr.mlr-org.com/.

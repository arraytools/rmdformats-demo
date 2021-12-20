The Rmd file is used to demo the gallery feature in HTML files. You can download the file `table-small-demo.html` to see the result.

The original Rmd file `table-contest-rmd.Rmd` comes from ["Using gt, gtExtras and openair to present air quality monitoring data"](https://github.com/jack-davison/rstudio_table-contest_2021) RStudio Table Contest 2021.

In order to demo the lightbox gallery in HTML created from rmarkdown files, I save the necessary R objects files in `our_table.rda` created from kniting `table-contest-rmd.Rmd` file.

I create a small Rmd file `table-small-demo.Rmd` for the demo purpose. You can create the HTML output file `table-small-demo.html` by running `Rscript -e "rmarkdown::render('table-small-demo.Rmd')"` in the command line or just knit the file assuming you have installed the required R packages.

More resources:

* [The rmdformats package](https://bookdown.org/yihui/rmarkdown/rmdformats.html) from R Markdown: The Definitive Guide
* [rmdformats](https://github.com/juba/rmdformats) package



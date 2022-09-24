
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mclmtutorials

<!-- badges: start -->
<!-- badges: end -->

The goal of mclmtutorials is to gather
[{learnr}](https://rstudio.github.io/learnr/) tutorials related to the
[{mclm} package](https://masterclm.github.io/mclm/).

## Installation

You can install the development version of mclmtutorials from
[GitHub](https://github.com/masterclm/mclmtutorials) with:

``` r
remotes::install_github("masterclm/mclmtutorials")
```

You will also need to install the development versions of {learnr} and
{gradethis} as well as {mclm}.

``` r
remotes::install_github("rstudio/learnr")
remotes::install_github("rstudio/gradethis")
remotes::install_github("masterclm/mclm")
```

## Example

After installing the package, you can run a tutorial by going to the
“Tutorial” tab in RStudio and selecting the tutorial you’re interested
in. Alternatively, you can run
`learnr::run_tutorial("tutorial_name", package = "mclmtutorials")` on
the console.

The available tutorials are:

-   *First steps with MCLM* (“freq_and_conc”), a general introduction to
    the mclm package, from reading corpus files and generating frequency
    lists to reading concordance lines.
-   *All about frequency lists* (“freqlists”), an introduction to the
    `freqlist` class in mclm.
-   *Keyword analysis* (“keywords”), to run keyword analysis on mclm.
-   *Starting with regular expressions* (“regex”), to learn and practice
    how to work with regular expressions in the mclm package.
-   *Encoding* (“encoding”), a very brief exercise with file encodings.

The following code will launch the introductory tutorial:

``` r
learnr::run_tutorial("freq_and_conc", package = "mclmtutorials")
```

The tutorials contain different degrees of explanation, code to copy,
quizzes and code exercises with evaluation.

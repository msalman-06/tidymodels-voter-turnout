# tidymodels-voter-turnout

Lightning talk for CSI2300 — exploring the `tidymodels` package and applying it to voter turnout prediction.

## Files

| File | What it is |
|------|-----------|
| `vignette_01_urchins.qmd` | Walkthrough of the official tidymodels "Build a Model" tutorial (urchins data) |
| `vignette_02_turnout.qmd` | My own application — predicting county-level voter turnout |
| `tidymodels_slides.qmd` | Slide deck for the lightning talk |

## Packages needed

```r
install.packages(c("tidymodels", "tidyverse", "vip",
                   "dotwhisker", "palmerpenguins", "knitr"))
```

For PDF slides:
```r
install.packages("tinytex")
tinytex::install_tinytex()
```

## Data sources

- Vignette 1: Constable (1993) urchins data via tidymodels.org/start/models/
- Vignette 2: Simulated data structured after the MIT Election Data Science Lab county-level returns dataset (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ)

## Citations

```r
citation("tidymodels")
citation("vip")
```

---
title: "Business Intelligence Project"
author: "<Timothy Obosi>"
date: "<>"
output:
  github_document: 
    toc: yes
    toc_depth: 4
    fig_width: 6
    fig_height: 4
    df_print: default
editor_options:
  chunk_output_type: console
---

# Student Details

|                                              |              |
|----------------------------------------------|--------------|
| **Student ID Number**                        | 134100       |
| **Student Name**                             |Timothy Obosi |
| **BBIT 4.2 Group**                           |Group B       |
| **BI Project Group Name/ID (if applicable)** |Real estate   |

# Setup Chunk

**Note:** the following KnitR options have been set as the global defaults: <BR> `knitr::opts_chunk$set(echo = TRUE, warning = FALSE, eval = TRUE, collapse = FALSE, tidy = TRUE)`.

More KnitR options are documented here <https://bookdown.org/yihui/rmarkdown-cookbook/chunk-options.html> and here <https://yihui.org/knitr/options/>.

```{r setup, include=FALSE}
library(formatR)
knitr::opts_chunk$set(
  warning = FALSE,
  collapse = FALSE
)
```

# Understanding the Dataset (Exploratory Data Analysis (EDA))

## Loading the Dataset

### Source:

The dataset that was used can be downloaded here: *\<provide a link\>*

### Reference:

*\<Cite the dataset here using APA\>\
Refer to the APA 7th edition manual for rules on how to cite datasets: <https://apastyle.apa.org/style-grammar-guidelines/references/examples/data-set-references>*

```{r Install Packages, echo=TRUE, message=FALSE, warning=FALSE}
## formatR - Required to format R code in the markdown ----
if (!is.element("formatR", installed.packages()[, 1])) {
  install.packages("formatR", dependencies = TRUE,
                   repos="https://cloud.r-project.org")
}
require("formatR")


## readr - Load datasets from CSV files ----
library(readr)
properties <- read_csv("data/properties.csv")
View(properties)
```


# Provide the executable R code inside the various code chunks as guided by the lab work.
```

...to be continued
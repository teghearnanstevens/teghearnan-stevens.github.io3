---
title: "Task/project name here"

editor: visual
execute:
  keep-md: true
#  freeze: true alternative way to only render this doc and not all 
# maybe the gh-pages setting cause all to render and docs dont? more testing

date: "December 09, 2024"
warnings: false
format:
  html:
    df-print: paged
    code-fold: true
    code-line-numbers: true
---





## Dow-Jones Industrial Average Returns




::: {.cell}

```{.r .cell-code}
# Libraries
if (!require("pacman")) install.packages("pacman")
pacman::p_load(reader, ggplot2)
```
:::




testing freeze: auto

goal is to shorten reder website times by only rendering updated files.

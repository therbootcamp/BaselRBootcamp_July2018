# organisation
Organisation planning for BaselRBootcamp

Key Links

- 2018April Repository: https://github.com/therbootcamp/BaselRBootcamp_2018April


## Slides

Use the following template for the slide YAML

```
---
title: "TITLE"
subtitle: ""
author: "The R Bootcamp<br/><a href='https://therbootcamp.github.io'>www.therbootcamp.com</a>"
output:
  xaringan::moon_reader:
    css: ["default", "../_css/my-theme.css"]
    lib_dir: libs
    nature:
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
      ratio: '16:9'
---
```

To knit sides so that the `my-theme.css` file is found, run the following (adjust content to fit specific slides)

```
# Code to knit slides
xaringan::inf_mr('_sessions/D2S3_MachineLearning/MachineLearning.Rmd')
```

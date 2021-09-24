# OMIS_482_Project
Group A repository for OMIS 482 R Studio project 
---
title: "the_movie_reviewers"
author: "Gary Dhami, Amelasky Mendez, Tyler Williams, Rachel Worden"
date: "`r format(Sys.time(), '%d %B, %Y')`" 
output: 
  html_document:
    
    theme: flatly
    toc: TRUE
    toc_float: TRUE
    code_download: TRUE
editor_options: 
  chunk_output_type: console
---

```{r setup, include=FALSE, cache = F}
knitr::opts_chunk$set(
  echo = TRUE,
  error = TRUE,
  warning= FALSE,
  message= FALSE)

---
title: "R for Environmental Economics"
tags:
  - R
  - environmental economics
  - forest
  - air pollution
  - data analysis and graphing
  - wrangling and graphing
  - matching
  - SIR model
authors: 
  - name: Vikram Dayal
    affiliation: 1 
  - name: M Rahul
    affiliation: 2
affiliation:
  - name: Institute of Economic Growth, New Delhi, India
    index: 1
  - name: Indian Economic Service, Government of India, New Delhi, India
    index: 2
date: 7 June 2021
bibliography: paper.bib
---

# Summary

We present a short module that demonstrates the use of the versatile open-source software R in environmental economics courses. We look at several examples in environmental economics — forests, air pollution, and the spread of biologically invasive species like the coronavirus. We begin at a very basic level both in terms of economics and R — starting with vectors and data frames. We then show how to wrangle and graph data, estimate simple models, and use a for loop for simulation. Students can get a feel for doing environmental economics, for writing R code, and also build a foundation for future skill acquisition.

# Statement of Need

“Doing” economics as a part of learning economics has been well recognised in the economics education literature [@Bartlett; @Siegfried; @Hansen]. Teachers of economics can choose from a variety of software to help students learn actively by doing economics. Versatility, availability, relevance to the course being taught, and possibilities of future use are key criteria for choosing software.from our experience with teaching [@Rstat] to diverse audiences, both with and without strong economics backgrounds, we feel that because R is versatile, freely available, and allows you to access cutting edge tools, it should merit attention as a possible software in environmental economics courses. R’s amazing graphing and data handling capabilities are documented in [@Healy] and [@Unwin], and since we typically spend most time working with data before we can graph it, we feel that R is one of the best possible software for graphing data. System dynamics softwares like Stella and Vensim can make simulating dynamic systems very easy, but @Duggan:2016 has shown how R can be used for system dynamics modelling. A potential stumbling block in using R is the need to write code, and this paper has been carefully crafted so that students can navigate the R learning curve.

# Learning objectives

The objective of the course material is to provide an introduction to students of environmental economics to using R. It is expected that the material will help students:

- learn basics of R and be able to navigate R studio
- learn basic data analysis using R
- learn basic data wrangling and graphing
- learn to use coarsened exact matching in R
- learn to simulate a simple SIR model in R

# Content

We present several examples in environmental economics ranging from forests to air pollution, and the spread of biologically invasive species like the coronavirus. In lesson 1, we show the layout of RStudio through which we can work with R and introduce vectors and dataframes. In lesson 2, we show how simple models can be estimated with R. R is excellent for wrangling and graphing, and we repeatedly illustrate this feature, providing a detailed example in lesson 3. A strength of R is that researchers across the world develop and contribute packages that are cutting edge in nature; we provide an example of using an R package that incorporates recent research on matching methods in lesson 4. Finally, to simulate difference equations, we introduce for loops and functions in lesson 5. 

# Instructional design

The material can be used in a workshop or independently worked upon. The different examples illustrate the versatility of R — though the numerical examples are basic, we also replicate data analysis results from three published papers and provide links to their data. There are five Rmd files numbered from 1 to 5. The material does not assume any previous knowledge of R and therefore starts with the basics in the first Rmd file. Either in labs or in flipped classrooms, students can work through the examples proceeding interactively line by line, learning from each other with some inputs from the instructor, and the source text and papers can be discussed alongside.



# Experience of use in teaching

The materials have most recently been used in a master class at the Sixth International Conference on South Asian Economic Development, South Asia University, New Delhi held from 25 to 27 February 2021. The material was also used in a virtual workshop on research methods in environmental and resource economics with R from May 17-21, 2021 organized by the South Asian Network for Development and Environmental Economics (SANDEE) at the International Center for Integrated Mountain Development (ICIMOD), East-West University (EWU), and Goa University (GU).

# References


---
title: "Setup an autocompiler for compiling text to pdf"
author: Yingqi Jing
affiliation: University of Zurich
date:
linestretch: 1.15
mainfont: Libertinus Serif
bibliography: /Users/jakejing/switchdrive/bib/references.bib
csl: /Users/jakejing/switchdrive/bib/unified-style-linguistics.csl
link-citations: TRUE
tables: TRUE
margin: 2.5cm
header-includes:
  - \usepackage{gb4e}
  - \usepackage{standalone}
  - \usepackage{threeparttablex}
  - \usepackage{longtable}
  - \usepackage{amsmath}
  - \usepackage{caption}
  - \usepackage{subcaption}
  - \usepackage{upgreek}


abstract: "To compile the main.md file, you simply need to type ctrl+r. It will automatically compile the file and convert it into pdf."
---


\setlength{\parskip}{4pt}
\renewcommand{\labelitemi}{-}
\clubpenalty = 10000
\widowpenalty = 10000
\displaywidowpenalty = 10000

\let\eachwordone=\itshape
\let\eachwordtwo=\small
\def\gltoffset{0.5ex}




# Introduction

In order to make things work. You need to have keymapping in you vimrc file.


# Data and Methods

This is the part for method and data. New change.

## Subsection for data

This is the subsection. To test the file. New


# Conclusions



\setlength{\parskip}{0pt}
\raggedright
\setstretch{1}


# References



---
week: 5
title: "Review and Refresher"
abstract:  >
  In this review and refresher notebook we mix some review work with some of the concepts we'd like you to develop and understand as you progress through the course. The review work focuses on the use of probability, correlation, pandas and the jupyter notebook. Most of the code you need is provided in the notebook, there are a few exercises to help develop your understanding. 
layout: notebook
venue: Intel Lab, William Gates Building
author:
- family: Lawrence
  given: Neil D.
  gscholar: r3SJcvoAAAAJ
  institute: University of Cambridge
  twitter: lawrennd
  url: http://inverseprobability.com
time: "10:00"
date: 2021-11-05
transition: None
reveal: false
ipynb: true
---

\section{Introduction}

\notes{Welcome to the review and refresh practical. This work is for you to remind yourself about the ways of using the notebook. You will have a chance to ask us questions about the content on 9th of November. Within the material you will find exercises. If you are confident with probability you can likely ignore the reading and exercises which are listed from @Rogers:book11 and @Bishop:book06. There should be *no need* to purchase these books for this course. The suggestions of sections are there just as a reminder.}

\notes{We suggest you run these labs in *Google colab*, there's a link to doing that on the main lab page at the top. We also suggest that the first thing you do is click `View`->`Expand sections` to make all parts of the lab visibile.}

\notes{We suggest you complete at least Exercises 4-9.}

\include{_ads/includes/ads-notebook-setup.md}

\include{_systems/includes/nigeria-nmis-data-systems.md}
\include{_ml/includes/probability-intro.md}

\newslide{}

\figure{\includeyoutube{GX8VLYUYScM}{600}{450}}{MLAI Lecture 2 from 2012.}{mlai-lecture-2012}


\addreading{@Rogers:book11}{Section 2.2 (pg 41–53)}
\addreading{@Rogers:book11}{Section 2.4 (pg 55–58)}
\addreading{@Rogers:book11}{Section 2.5.1 (pg 58–60)}
\addreading{@Rogers:book11}{Section 2.5.3 (pg 61–62)}


\addreading{@Bishop:book06}{Probability densities: Section 1.2.1 (Pages 17–19)}
\addreading{@Bishop:book06}{Expectations and Covariances: Section 1.2.2 (Pages 19–20)}

\addreading{@Bishop:book06}{The Gaussian density: Section 1.2.4 (Pages 24–28) (don’t worry about material on bias)}
\addreading{@Bishop:book06}{For material on information theory and KL divergence try Section 1.6 & 1.6.1 (pg 48 onwards)}

\reading 

\addexercise{@Bishop:book06}{Exercise 1.7}
\addexercise{@Bishop:book06}{Exercise 1.8}
\addexercise{@Bishop:book06}{Exercise 1.9}

\exercises

\section{A First Analysis}

\include{_data-science/includes/covid-vaccination-and-simpsons-paradox.md}


\include{_data-science/includes/correlation-coefficients.md}

\section{A Second Analysis}
\include{_datasets/includes/bmi-steps-data.md}

\subsection{BMI Steps Analysis}

\codeassignment{The hypothesis is that the number of steps taken may have an effect on the BMI. Using what you've learnt about correlation and probability explore this hypothesis using the box below.}{}{15}


\thanks

\reading

\exercises


\references

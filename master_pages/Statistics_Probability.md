---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Statistics and Probability | R
---

<h1 align="center"> Statistics and Probability with R</h1>

<p align="center"><img src="https://www.uu.se/digitalAssets/806/c_806212-l_1-k_image.jpg"></p>

<h2> Table of Contents </h2>

- [Steps of Statistical Methods](#steps-of-statistical-methods)
- [Statistics Introduction](#statistics-introduction)
- [Data Descriptors (Descriptive Statistics)](#data-descriptors-descriptive-statistics)
- [Population and Samples](#population-and-samples)
- [Probability Theory |](#probability-theory-)
- [Probability Theory ||](#probability-theory--1)


## Steps of Statistical Methods

  1. **Gathering data** the knowledge of collecting sample to represent the whole population.
  2. **Describing and visualizing data** the knowledge of summarizing and visualize the data by numbers, graphs, and charts.
  3. **Making conclusions** Statistics from the data in the sample is used to make conclusions about the whole population. Probability theory is used to calculate the certainty that those statistics also apply to the population.




## Statistics Introduction

- what is statistics?
  - Statistics is the field of science that deals with the collection analysis, interpretation, and use of data to make decisions and draw conclusions.
- Statistics Objectives / Types
  - *Descriptive Statistics* Describe and Summarize data
  - *Relational Statistics* Relationship between two or more variables. (correlation, causality, etc.)
  - *Inferential Statistics* Generalization from samples to populations and hypthesis testing.
- What are Data
  - *Quantitative* numerical or binary (audio files or images)
    - could be discrete or continuous
  - *Qualitative* categorical
- Main types of statistical studies:
  - *Observational* 
  - *Experimental*

## Data Descriptors (Descriptive Statistics)

- The most common descriptive statistics:
  - *central tendency measures* called **averages**
    - Mean: the arithmetic mean. Also there is a weighted mean
    - Mode: the most frequent value in a data set
    - Median: the middle index of sorted values. could be unimodela, bimodal, trimodal, etc.
  - *dispersion measures*
    - Range: the difference between minimum and maximum
    - Standard deviation or variance: the average (mean) of the squared deviation of each value in a data set, of n elements, from the data set mean
    - Median absolute Difference (MAD): the median of the difference between data set and their true median.

## Population and Samples 

- The terms `population` and `sample` are important in statistics and refer to key concepts that are closely related.
  - *Population* Everything in the group that we want to learn about.
  - *Sample* A part of the population.
- For good statistical analysis, the sample needs to be as "similar" as possible to the population. If they are similar enough, we say that the sample is representative of the population.
- The sample is used to make conclusions about the whole population. If the sample is not similar enough to the whole population, the conclusions could be useless.
- - *Parameter* A number that describes something about the whole **population**.
- *Sample Statistics* A number that describes something about the **sample**.
  - For every parameter we want to learn about we can get a sample and calculate a sample statistic, which gives us an estimate of the parameter.

** Some definitions are taken from: [W3Schools](https://www.w3schools.com/statistics/statistics_parameters_and_statistics.php)


## Probability Theory |

- *Random experiment* can result in different outcomes every time it is repeated, even though it is repeated in the same manner.
- *Sample Space* the set of all possible outcomes of that random experiment.
  - Discrete: could be finite countable or infinite countable set of outcomes.
  - Continuous: an interval of real numbers
- *Event* a subset of the sample space of a random experiment.
- *Probability* is a numerical measure between 0 and 1 that quantifies how likely an event A will occur.
  - *Marginal Probability* : P(A) the probability that event A will happen.
  - *Conditional Probability*: P(A/B) the probability of event A happends given that event B already happened.
  - *Joint Probability*: P(A,B) the probability that events A and B happen together at the same time.
- There are many types of how to calculate the probability:
  - Frequentist Probability which is the `numbre of times event A occurs / n times`
- Probability Axioms:
  -  `0 <= P(E) <= 1`
  -  `P(S) = 1`  probability of the sample sapce is equal to 1
  -  If `A intersection B = Phi` (Empty set), then `the probability of their union is the sum of their probability`.
  -  P(E`) = 1 - P(E)
  -  `P(Phi) = 0`
-  Cumulative probability. example: `P(X<=2)  = P(X=1) + P(X=2)`
-  *Probability mass functions (pmf)* are used to describe **discrete** probability distributions. While *probability density functions (pdf)* are used to describe **continuous** probability distributions.


## Probability Theory ||

- **Addition Rule** - Probability of a Union
  - For two events A and B, the probability of union implies that:
    - `P(A union B) = P(A) + P(B) - P(A intersection B)`
    - if A and B are mutually exclusive events; that means `A intersection B = phi`, thhe union implies: `P(A union B) = P(A) + P(B) `
- **Conditional Probability**
  - it the probability of event A given that event B occurs.
    - `P(A|B) = P(A intersection B) / P(B)`
    - Conditional Probability reduces the sample space from S to B. *it make sense because we divide on P(B) in the conditional probability, but in the marginal probability we was dividing by P(S)*
    - If B is known to have occured, then A can occur only if (A intersection B) occurs. *it make sense because if the intersection doesn't occurs, it means it will be with zero so there is no conditional probability*.
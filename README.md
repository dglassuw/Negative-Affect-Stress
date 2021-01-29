# About this project

This repo includes a compiled .rmd for a contained project using longitudinal mixed models, both Bayesian and Inferential. In this course project for a graduate level statistics class, I used publicly available data from the National Study of Daily Experiences (1996-1997) through the Midlife in the United States study to examine relationships between negative affect, daily stress experiences, age, and biological sex assigned at birth (original data term: gender).

The data are available [here](https://www.icpsr.umich.edu/web/NACDA/studies/3725#:~:text=The%20National%20Study%20of%20Daily,a%20subsample%20of%20MIDUS%20respondents)

**Abstract**

Negative affect, which is a cumulative term for emotional or psychological disposition including propensity towards depression, nervousnesness, restlessness, anger, and sadness, has been examined in relation to a host of biobehavioral factors. Over the lifecourse, individuals encounter a variety of stressors and embody varying emotional and physiological states. There is considerable evidence that there is both high intradindividual variation in responsivity to stressors and reporting negative affect in relation to daily stresses experienced[\@mroczek2004a] Responsivity to stress and likelihood of reporting negative affect varies by age and biological sex assigned at birth[\@mroczek2004]. In this project, I investigate whether negative affect varies systematically across time for individuals, and whether between individual change in negative affect varies over time by change in daily stress severity, biological sex, and age. I use longitudinal linear mixed modeling both Inferential and Bayesian to answer these questions using publicly available data from the National Study of Daily Experiences (NSDE). The SDE is a subset of the MIDUS Cohort in 1996-1997 with 8 measurement occasions across a 1 year period for individuals ages 20-74.

**Motivation and project objectives**

The intraindividual variation of negative affect (a summed score relating to experiences of depressive mood, nervousness, and more) in relation to stress reactivity (reported severity of stressors experienced) warrants further investigation by age and biological sex in a longitudinal design. My statistical project objectives were to investigate the following questions:

How is negative affect impacted by daily change in stressors for individuals & between individuals?

How is between-individual variation in negative affect impacted by daily stress severity, age, and sex?

**Key Findings**

Exploratory analyses of negative affect over time across sex and age indicate further investigation with wide variation in initial status (intercepts) and change over time (slopes).

The Bayesian and Inferential models indicate that females have higher initial status of negative affect compared to males. Stress severity appears to increase over time, but age my be protective to either experiencing or reporting negative affect in response to daily stressors. Further investigation outside of a statistics course is warranted to examine relationships between perceived stress, negative affect, and age. Future work may compare age groups, implement a robust longitudinal design beyond 1 year, and incorporate biomarkers relevant to stressful experiences.

**Packages Utilized**

-   nlme for inferential mixed effects models

-   brms for Bayesian mixed effects models

-   ggplot2 for data visualization

-   pander for fixed effects from nlme models

**Data citation**

Almeida, David M. Midlife in the United States (MIDUS 1) National Study of Daily Experiences (NSDE), 1996-1997. Inter-university Consortium for Political and Social Research [distributor], 2017-11-17. <https://doi.org/10.3886/ICPSR03725.v5>

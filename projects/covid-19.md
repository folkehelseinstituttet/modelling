---
layout: page
title: "COVID-19 Modelling"
---



During the COVID-19 pandemic our team provided scenario and situational awarness modelling to suppert the Norwegian response to the pandemic. 


#### Situational Awareness
Our work on situational awarness was based on a metapoulation model, published [here](https://doi.org/10.1371/journal.pcbi.1010860), and we provided daily and weekly repports to the Norwegian goverment and public. All the reports reports can be found [here](https://www.fhi.no/ss/korona/koronavirus/koronavirus-modellering/).

The reports included: 
- Estimates of national and regional reproduction numbers
- Short-term forecasts of hospital admissions and burden
- Mobility reports based on mobile phone data from Telenor

Key parts of the modelling included challenging parameter estimation for a large number of parameters in a stochastic model. We developed one approach based on [Approximate Baysian Computation](https://doi.org/10.1371/journal.pcbi.1010860) and one based on [Sequential Monte Carlo](https://academic.oup.com/jrsssa/article/186/4/616/7145945).

![Estimates of regional reproduction numbers]({{'/assets/img/sit-rep.png'|absolute_url}})

Example of estimates regional reproduction numbers from the [report](https://www.fhi.no/contentassets/e6b5660fc35740c8bb2a32bfe0cc45d1/vedlegg/nasjonale-og-regionale-rapporter/national_regional_model_3_november_2021.pdf) published on 4th of November 2021. 


The situational awarness modelling was a collaboration betwen the Norwegian Institute of Public Health, the University of Oslo, the Norwegian Computing Center through the [BigInsight project](https://www.biginsight.no/). 


#### Scenario Modelling

Another key part of the pandemic response was scenario modelling for risk evaluations and to provide evidence for policy decisions. We used multiple different models for different questions, with a main empahsis on using both a metapopulation model and and individual based model. We provided modelling for the following topics, linked to some example reports.

- [Risk evaluations published by the Norwegian Institute of Public Health](https://www.fhi.no/contentassets/e6b5660fc35740c8bb2a32bfe0cc45d1/vedlegg/nasjonale-og-regionale-rapporter/winter_scenarios_2022_2023.pdf)
- [Long term scenario with new variants](https://www.fhi.no/contentassets/e6b5660fc35740c8bb2a32bfe0cc45d1/vedlegg/nasjonale-og-regionale-rapporter/modelling-scenarios-for-the-sars-cov-2-omicron-voc-26.01.2022.pdf)
- [Prioritization of vaccines](https://www.fhi.no/contentassets/d07db6f2c8f74fa586e2d2a4ab24dfdf/2020-12-v2-anbefalinger-og-prioriteringer-2-utgave-korrigert-forside.pdf)
- [Regional prioritisation of vaccines](https://www.medrxiv.org/content/10.1101/2023.08.16.23294112v1)
- [Economic evaluation of non-pharmaceutical interventions](https://www.regjeringen.no/contentassets/7f1fdef23b72488da28fde24416425e6/20220405_holden-iv_hovedrapport.pdf)

The Individual Based Model was developed from a previous [IBM used for MRSA](https://www.pnas.org/doi/abs/10.1073/pnas.1900959116). The soon-to-be published article on [regional prioritisation of vaccines](https://www.medrxiv.org/content/10.1101/2023.08.16.23294112v1) includes a description of both of the main models used and important results about how to prioritise vaccines.


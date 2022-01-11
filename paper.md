---
title: 'HDI: High Demand Image Analysis using Deep Learning for Microcirculation Image Analysis'
tags:
  - Python
  - Django
  - React
  - Tensorflow
authors:
  - name: Maged Abdalla Helmy^[co-first author]
    affiliation: 1
  - name: Eric Jul
    affiliation: 1
  - name: Paulo Ferreira
    affiliation: 1
  - name: Trung Tuyen Truong
    affiliation: 2
affiliations:
 - name: Department of Informatics - University of Oslo
   index: 1
 - name: Department of Mathematics - University of Oslo
   index: 2
date: 13 August 2017
bibliography: paper.bib
---

# Summary

Analyzing the microvascular supply by quantifying the capillary area can predict life-threatening diseases like Sepsis.
Estimating the capillary area knowledge can assist medical personals in the decision-making process towards the patient's treatment.
Readily available handheld microscopes have allowed the ease of capturing capillary images from the microcirculation system.
However, quantifying these capillaries in the captured images remains a tedious labor-intense job subject to inter-observer variability.
This paper presents an end-to-end system that can detect the capillaries and quantify the capillary area captured by these handheld microscopic devices.
We evaluated our system with an industrial MedTech partner specialized in tailored patient therapy by assessing the microcirculation system.
This system has a high clinical relevance because it significantly reduces the time to quantify capillaries from 2 minutes to less than 2 seconds by automating the laborious task of annotating the capillaries in the image.
Furthermore, it eliminates inter-observer variability by standardizing the analysis process using deep learning algorithms.

# Statement of need

Medical personals and clinical researchers can spend countless hours manually quantifying the capillary density in a microcirculation image captured from a microscope.
This manual analysis method can be a bottleneck for providing the results within a reasonable time frame when hundreds of patients request their capillary density to be quantified. Furthermore, this method is prone to human errors and inter-observer variability between the clinical researchers. This statement of need is further strengthened by the research paper created by the European Society of Intensive Care Medicine on the assessment of sublingual microcirculation in critically ill patients \cite{ince2018second} where they stated the need for developing a system that can automatically quantify capillaries. Thus, the main goal of this software is to reduce the time needed for capillary quantification while maintaining comparable accuracy of analysis which is 85% [@Pearson:2017] 


# Figures

Figures can be included like this:
![Caption for example figure.\label{fig:example}](figure.png)
and referenced from text using \autoref{fig:example}.

Figure sizes can be customized by adding an optional second parameter:
![Caption for example figure.](figure.png){ width=20% }

# Acknowledgements

We acknowledge contributions from Brigitta Sipocz, Syrtis Major, and Semyeong
Oh, and support from Kathryn Johnston during the genesis of this project.

# References

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
This manual analysis method can be a bottleneck for providing the results within a reasonable time frame when hundreds of patients request their capillary density to be quantified. Furthermore, this method is prone to human errors and inter-observer variability between the clinical researchers. This statement of need is further strengthened by the research paper created by the European Society of Intensive Care Medicine on the assessment of sublingual microcirculation in critically ill patients [@ince:2018]  where they stated the need for developing a system that can automatically quantify capillaries.
The development of such automated systems makes microcirculation analysis feasible in a clinical environment (i.e., hospitals).
Thus, the main goal of this software is to reduce the time needed for capillary quantification while maintaining comparable accuracy of analysis which is 85%.

# State of the Art:

The authors have provided an extensive literature review in section 2 of the paper `CapillaryNet: An Automated System to Analyze Microcirculation Videos from Handheld Vital Microscopy` [@helmy:2021].

# System Design

The sysem design has been illustrated using 3 figures.

Figure \autoref{fig:context} starts with the high level overview of the system and shows the System Context.
It consists of

Figure \autoref{fig:container} shows the system containers within the system context.
It consists of

Figure \autoref{fig:component} is a detailed view of the system containers and shows the system components.
It consists of



![The System Context View figure.\label{fig:context}](context.png)

![The System Container View figure.\label{fig:container}](container.png)

![The System Component View figure.\label{fig:component}](component.png)



# Acknowledgements

The authors would like to thank the Research Council of Norway for providing the necessary funds for this project: Industrial Ph.D. project nr: 305716 and BIA project nr: 282213. The authors would also like to thank the MedTech Partner ODI Medical AS for providing the data, hardware, and support to test and evaluate this project.

# References


# Development of New Approach Methodologies for Next-Generation Risk Assessment through Integrated QSAR-PBPK Modeling 

## Background

Currently, it is estimated that over **100,000 industrial chemicals** are in commerce, with hundreds of new substances introduced annually. Traditional **'one-by-one' animal testing** is fundamentally incapable of keeping pace with this rate of production, leaving significant data gaps in human health protection. 

This is particularly critical, for instance, for very high concern compounds like *Endocrine Disrupting Chemicals* (**EDCs**), which can interfere with hormonal systems at low doses and lead to developmental, reproductive, and metabolic disorders. For that reason, over the last decade, the need for *new approaches* in toxicology and chemical safety assessment has become increasingly urgent. 

Scientific and regulatory bodies are aware that a transition is necessary, moving from animal-based observational studies to a more mechanistic and human based framework. 

**Animal research is time-consuming, expensive, and raises significant ethical concerns.**

Therefore, this evolution is being driven by **New Approach Methodologies** (**NAMs**), which aim to modernize chemical risk assessment by integrating *in chemico*, *in silico*, and *in vitro* workflows, as defined by EURL ECVAM. 
With *in silico* modeling, we can rapidly prioritize these high-concern substances, predicting how they accumulate and interact with human biological systems without the years of labor and ethical burden required by in vivo assays.
A powerful tool to achieve this transition is integration between **Quantitative Structure-Activity Relationship** (**QSAR**) modeling and **Physiologically Based Pharmacokinetic** (**PBPK**) modeling. 

Unlike animal research, this in silico approach is fast, flexible, and generates data that can be used for further studies.
QSAR models allow us to predict molecular and biochemical properties from *chemical structures* (e.g., LogP, pKa, partitioning) that can subsequently be used in a PBPK model, which acts as a virtual human simulator.
By using QSAR to identify **ADME** predictors (**Absorption, Distribution, Metabolism, and Excretion**) and combining this approach with **Quantitative In Vitro to In Vivo Extrapolation** (**QIVIVE**), a complete system is established.

This system can be used to test specific compounds for specific endpoints while avoiding animal testing and ensuring scientific reliability. 
This workflow is perfectly aligned with the recent **OECD Guidance Document No. 331**, which provides the framework for the characterization and reporting of these kinetic models for regulatory acceptance.
To reach this goal, several major European projects are currently collaborating to modernize chemical safety.
Among these, the **European Partnership for the Assessment of Risks from Chemicals** (**PARC**) stands as a flagship Horizon Europe initiative designed to bridge the gap between innovative science and regulatory policy. This research is strategically integrated into the PARC project, and as an active member, this PhD project will directly benefit from and contribute to the development of harmonized protocols for **Next-Generation Risk Assessment** (**NGRA**), ensuring the tools developed are both scientifically robust and ready for regulatory implementation.

## Specific objectives

The primary goal of this PhD thesis is to develop a **NAM-based** computational framework that integrates **Quantitative Structure-Activity Relationship** (**QSAR**) and **Physiologically Based Pharmacokinetic** (**PBPK**) modeling as a high-throughput tool for human health risk assessment. To achieve this, the following specific objectives are defined:

1) Implementation of **QSAR** models to predict **ADME** (**Absorption, Distribution, Metabolism, and Excretion**) parameters directly from molecular descriptors. 
These include critical chemical parameters such as:
 - the Apparent Permeability ($P_{app}$), 
 - the fraction unbound to plasma proteins ($f_{up}$), 
 - and intrinsic hepatic clearance ($Cl_{int}$).

2) Subsequently, with the gathered information, mechanistic **PBPK** models will be developed to simulate toxicokinetic of prioritized chemical classes (e.g., EDCs, PFAS, pesticides, or emerging contaminants). 
These models will be refined to cover **different life stages** and **sex-specific** physiological variations, ensuring the protection of sensitive populations.

3) Another objective is the performance of **Quantitative In Vitro to In Vivo Extrapolation** (**QIVIVE**) to calculate the human equivalent risk directly from in vitro bioactivity results. This involves converting in vitro concentration-based thresholds into **Human Equivalent Doses** (**HED**), allowing or a direct comparison with real-world human exposure levels to characterize risk.

4) Development of a tool integrating **QIVIVE PBPK-QSAR** for open access use by the scientific community. From a regulatory standpoint, the developed tests and the workflow used will align with international regulatory standards, specifically the OECD Guidance Document 331, to ensure scientific confidence and regulatory acceptance.
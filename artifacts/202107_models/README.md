MDE Artifacts: Quality Guidelines for Research Artifacts in Model-Driven Engineering (Research Artifact)

This is directory contains the research artifact for the article 
_Quality Guidelines for Research Artifacts in Model-Driven Engineering_.
This article has been accepted the Foundations Track of the 
MODELS'21 conference as a Technical paper[^1].

#  What this artifact does?

In this artifact, you will find: 
(1) Text documents (in _.docx_ format) with the full set of research practices extracted; 
(2) Various mind maps (in _.mm_ format) that we created to categorize research practices according to the 5W2H framework;
(3) Our guidelines, which include the 19 factual questions and 84 best practices specifically tailored to MDE research projects;
(4) Our Survey results (Between April-May 2021) and R scripts for analyzing our responses and drawing plots.
 
# Where it can be obtained?

## GitHub (main repository)

This artifact is hosted at the [damascenodiego/mdeartifacts.github.io](https://github.com/damascenodiego/mdeartifacts.github.io) repository.

## Zenodo
This repository is also archived on Zenodo that issued a DOI for our MoDELS'21 paper artifact:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5094439.svg)](https://doi.org/10.5281/zenodo.5094439)

## GitHub (fork repository for hosting the website)

There is a fork of this same repository which we maintain **only for the purpose of hosting the MDE Artifacts website** 
at the URL [https://mdeartifacts.github.io/](https://mdeartifacts.github.io/).

# How to replicate the results of this work?

To reproduce this work, we recommend you look at the text documents and mind maps available in 
our [data/](data/) folder. 
There you will find the docx files and mind maps with the practices and understand
how we organized our study.

To support the analysis of the survey results, we also provide a set of RScripts and 
an RStudio project where the interested researcher can generate the plots 
for the participants' role, challenges faced by MDE experts,
overall satisfaction of our respondents,
and plots for the top-priority practices.

Below, we depict an overall structure of this artifact.

          analysis/ # Rscripts to analyze our survey results
              img/                          # Plots generated from the analysis
          data/ # Data collected during the questionnaire 
              01_practices_extracted/   # Docx files with the 280 research practices extracted
              02_practices_labelling/   # Mind maps with the practices categorized using the 5W2H 
              03_guidelines_design/     # Our guidelines (19 factual questions + 84 best practices)
              04_guidelines_survey/     # Survey snapshot, and Anonymized results

## How to run the analysis of results?

To re-run our statistical analysis, 
please check our files **./analysis/analysis_0[1-4]*.Rmd**.
These files shall repeat our analysis and 
automatically generate most of the data we used to answer RQs 1 to 4.

## How could it be repurposed?

Currently, we find three ways this artifact could be repurposed:


1. This artifact can be adapted to particular types of MDE artifacts.
2. This artifact can be improved by incorporating different stakeholder's viewpoints
3. This artifact can be used to support researchers in designing domain-specific guidelines to their particular research fields.


# Requirements

For the running the survey, we recommend the [Google Forms platform](https://www.google.com/forms/about/).

For the running the statistical analysis, we recommend the following version of the R Statistical Package:


    **platform**:       x86_64-w64-mingw32          
    **arch**:           x86_64                      
    **os**:             mingw32                     
    **version.string**: R version 4.0.5 (2021-03-31)

Also, we recommend using the RStudio IDE Version 1.4.1106

The hardware settings used in this study were:


    **OS Name**:	  Microsoft Windows 10 Pro 
    **Version**:	  10.0.19042 Build 19042 
    **System Type**:  x64-based PC 
    **Processor**:	  Intel(R) Core(TM) i7-10510U CPU @ 1.80GHz 


# What are some useful references?

- N. R. Tague, **The quality toolbox**, 2nd ed. Milwaukee, Wis: ASQ Quality Press, 2005.
- Project Management Institute, Ed., **A guide to the project management body of knowledge
  / Project Management Institute** (PMBOK/PMI), Sixth edition. Newtown Square, PA:
  PMI, 2017.

# How to contact us?

For more information or to contribute with our project, feel free to contact one of the authors of this paper:

* Diego Damasceno <d.damasceno (at) cs (dot) ru (dot) nl>
* Daniel Strüber  <d.strueber  (at) cs (dot) ru (dot) nl>

[^1]: https://conf.researchr.org/track/models-2021/models-2021-technical-papers#Foundations-Track

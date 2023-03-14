# The role of Data Flow Diagrams in validating identified security threats- Replication package
This repository contains the data used to execute a control experiement to measure the role of a data flow diagram in validating security threats. The experiement was conducted in two universities, in the Netherlands and China.

### General overview
Several steps were followed in it's execution. 
First we prepared all textual materials. This included choosing relevant but comparable scenarios. To this end, we presented a kubernetes and a GitHub scenario for the first and confirming experiments. To further make the student's background knowledge comparable , for the subjects relevant to this study (security and selected scenarios), we developed training videos.
From the scenarios, we compiled 10 threats, each containing a unique thretad ID, threat description, assumption, affected components, and an associated STRIDE threat type. 5 of the threats were real and 5 were fabricated.
Additional reading materials, selcted book chapters on STRIDE were also made availabe.

To compare the role of the data flow diagram in validating threats, we 

### The Task
From the list of threats, the participants were required to identify the actual threats.



To aide in the replication, we have made available the following materials;
1. Scenario descriptions
2. List of threats
3. Sample entry questionnaire
4. Sample participants report and exit questionnaire
5. python notebook

## How to cite us
The scientific article describing design, execution, and main results of this study is available [here](https://www.google.com).<br> 
If this study is helping your research, consider to cite it is as follows, thanks!

```
@article{,
  title={},
  author={},
  journal={},
  volume={},
  pages={},
  year={},
  publisher={}
}
```

## Quick start
Here a documentation on how to use the replication material should be provided.

### Getting started



## Repository Structure
This is the root directory of the repository. The directory is structured as follows:

    template-replication-package
     .
     |
     |--- src/                             Contains the python notebook containing the step by step analysis of the data obtained from participants.
     |
     |--- documentation/                   Contains the scenario description for each experiement, and the list of threats for each scenario.
     |
     |--- data/                            Contains sample data obtained from participants reports. All identifiable information has been removed.
                         
  

Usually, replication packages should include:
* a [src](src/) folder, containing the entirety of the source code used in the study,
* a [data](data/) folder, containing the raw, intermediate, and final data of the study
* if needed, a [documentation](documentation/) folder, where additional information w.r.t. this README is provided. 

In addition, the replication package can include additional data/results (in form of raw data, tables, and/or diagrams) which were not included in the study manuscript.

## Replication package naming convention
The final name of this repository, as appearing in the published article, should be formatted according to the following naming convention:
`<short conference/journal name>-<yyyy>-<semantic word>-<semantic word>-rep-pkg`

For example, the repository of a research published at the International conference on ICT for Sustainability (ICT4S) in 2022, which investigates cloud tactics would be named `ICT4S-2022-cloud-tactics-rep-pkg`

## Preferred repository license
As general indication, we suggest to use:
* [MIT license](https://opensource.org/licenses/MIT) for code-based repositories, and 
* [Creative Commons Attribution 4.0	(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) for text-based repository (papers, docts, etc.).


# The role of Data Flow Diagrams in validating identified security threats- Replication package
This repository contains the data used to execute a control experiement to measure the role of a data flow diagram in validating security threats. The experiement was conducted in two universities, in the Netherlands and China.

### General overview
Several steps were followed in it's execution. 
First we prepared all textual materials. This included choosing relevant but comparable scenarios. To this end, we presented a kubernetes and a GitHub scenario for the first and confirming experiments. To further make the student's background knowledge comparable , for the subjects relevant to this study (security and selected scenarios), we developed training videos.
From the scenarios, we compiled 10 threats, each containing a unique thretad ID, threat description, assumption, affected components, and an associated STRIDE threat type. 5 of the threats were real and 5 were fabricated.
Additional reading materials, selcted book chapters on STRIDE were also made availabe.

To compare the role of the data flow diagram in validating threats, we proposed comparing it to a process diagram, a sequence diagram. To this end, we defined two treatment group. Intervention received both the DFD and sequence diagram while control group received only a sequence diagram.

### The Task
From the list of threats, the participants were required to identify/choose the actual threats.


### Available material for replication
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
     |--- src/                             Contains the python notebook with a step-by-step analysis of the data obtained from participants. We did not provide the actual data used in analysis, however, the data format follows the same columns contained in the excel files uploaded in the "Data folder" in this repository. 
     |
     |--- documentation/                   Contains the scenario description for each experiement, and the list of threats adopted from each scenario.
     |
     |--- data/                            Contains sample data obtained from participants reports. All identifiable information has been removed.
                         
  




## Preferred repository license
As general indication, we suggest to use:
* [MIT license](https://opensource.org/licenses/MIT) for code-based repositories, and 
* [Creative Commons Attribution 4.0	(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) for text-based repository (papers, docts, etc.).


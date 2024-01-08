## How Dataflow Diagrams Impact Software Security Analysis: an Empirical Experiment
This repository contains the replication package for the above paper, published at SANER 2024


### Cite
If you use the presented results in a scientific context, please cite as:

```bibtex
@inproceedings{Schneider24_DFDs_empirical_experiment,
    author      = {Simon Schneider, Nicolas E. Diaz Ferreyra, Pierre-Jean Queval, Georg Simhandl, Uwe Zdun, Riccardo Scandariato},
    title       = {How Dataflow Diagrams Impact Software Security Analysis: an Empirical Experiment},
    booktitle   = {2024 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER)}, 
    year        = {2024},
}
```


### Abstract 
Models of software systems are used throughout the software development lifecycle. Dataflow diagrams (DFDs), in particular, are well-established resources for security analysis. Many techniques, such as threat modelling, are based on DFDs of the analysed application. However, their impact on the performance of analysts in a security analysis setting has not been explored before. In this paper, we present the findings of an empirical experiment conducted to investigate this effect. Following a within-groups design, participants were asked to solve security-relevant tasks for a given microservice application. In the control condition, the participants had to examine the source code manually. In the model-supported condition, they were additionally provided a DFD of the analysed application and traceability information linking model items to artefacts in source code. We found that the participants (n = 24) performed significantly better in answering the analysis tasks correctly in the model-supported condition (41% increase in analysis correctness). Further, participants who reported using the provided traceability information performed better in giving evidence for their answers (315% increase in correctness of evidence). Finally, we identified three open challenges of using DFDs for security analysis based on the insights gained in the experiment.

### Content

1. [Analysis Results](https://github.com/tuhh-softsec/empirical_study_dfds/tree/main/results) The analysis of the results including all plots seen in the paper can be found in ```/results```. The folder contains a Jupyter Notebook file (```analysis.ipynb```), which can be used to replicate the complete analysis.

2. [Raw results](https://github.com/tuhh-softsec/empirical_study_dfds/tree/main/raw_results) The raw results (i.e., the data collected in the empirical experiment) are provided in ```/raw_results```, separated by condition and application that was analysed.

3. [Participant Resources](https://github.com/tuhh-softsec/empirical_study_dfds/tree/main/participant_resources) The resources given to the participants during the empirical experiment are contained in ```/participant_resources```.

4. [Organizational](https://github.com/tuhh-softsec/empirical_study_dfds/tree/main/organizational) The ethic commitee's approval, informed consent sheet, and introductory lecture that was held before the experiment are located in ```/organizational```



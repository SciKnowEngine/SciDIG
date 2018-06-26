# Scientific Knowledge Graphs (SciKnowGraph)

The underlying idea of this project is to develop linked data ontologies for given scientific domains and map data from sources into those representations based on ISI's 'Domain Insight Graph' (DIG) toolset as a development environment for our technology and our approach (http://dig.isi.edu). 

The semantic model for this work is driven by the concstruct shown in Figure 1. 
![Cycles of Scientific Investigation](https://sciknowengine.github.io/img/ske/cosi7.png)
**Figure 1: The Knowledge-Question-Experiment-Data ('KQED' model) of the Cycle of Scientific Investigation.**

The ontologies managed in this repository reflect this basic design and attempt to provide a semantic framework for supporting work within the KQED model. 

A few remarks about the KQED conceptual model:

1. The model describes a cyclic process that involves abstract entities \[Knowledge, Questions, Experiments, Data\] and processes \[analyze knowledge, design experiments, execute experimental designs, interpret data in context\]. 
1. All entities and processes in the section of the KQED model marked 'interpretations' are essentially domain specific. Knowledge in one domain may have an entirely different structure from that in another domain. Whereas the entities marked 'observations' (Experimental Designs, the process of executing such an experiment and the Data generated) may not require deep domain-specific representation. Thus we use a *generic, domain independent approach to describing Experimental Design and data* and *domain-specicic semantic models for Knowledge and Questions*. We discuss the underlying idea of separating observations from interpretations in this paper: [Burns & Chalupsky (2014) "It's all Made Up" AAAI Workshop on Discovery Informatics](http://www.aaai.org/ocs/index.php/WS/AAAIW14/paper/view/8735)
1. Our generic approach for modeling experimental design and data is called 'Knowledge Engineering from Experimental Design' (KEfED) and is described in various publications.
1. We are developing Neuroscience Domain Insight Graphs (neuDIGs) as a domain-specific model for systems-level neuroscience. We intend this work to provide a large-scale, pragmatic, common representation for neuroscientific knowledge that are primarily concerned with properties and characteristics of **neuron populations** that may (or may not) be explicitly identified by name. 

This repository houses the various ontologies involved in this work, linked data sets that conform to it, tooling, documentation and reasoning/modeling/inference systems. 

We maintain an active wiki to provide scientific documentation for this work: https://github.com/SciKnowEngine/SciKnowGraph/wiki

This project evaluated the FASTO ontoogy, which is a biomedical ontology for type 1 diabetes management reusing common standard ontolgies and medical terminologies. 
This projects investigated the efficiency of using LLMs for ontology evaluation across four task: 
1. General ontology flaw and pitfall detection.
2. Issues in reused ontologies and namespaces.
3. Outdated terms in the FHIR namespace.
4. Identifying if ontology still covers domain knowledge by creating new competency questions.

The input data of the LLM comprised: 
- The LLM was provided the FASTO .owl file, and its verbalized representation for all tasks.
- For Task 2, it was also provided the FASTO paper as well as the FHIR, SSN, OntoFood and DMTO ontology files. 
- For Task 3, it was also provided the result of task 2 for the FHIR namespace, and the FHIR R5 ontology.
- For Task 4, it was also provided the FASTO paper.

The LLM-based appraoch was compared to the results of standard tools such as OOPS! and ROBOT, of which the results are also available. 
Moreover, an LLM-enhanced version was investigated, where for Tasks 1 and 2, the reports and analysis of the standard tools were provided. 

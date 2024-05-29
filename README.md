Code & input data for the master's thesis

Topic: Patterns Analysis in the Online Assessment Processes Using Hierarchical Models

Based on the output data (external-43799.xml) from programming contest, an event log is generated. Output data contains the information about participants, tasks, submissions and their testing logs. 
Transformation is presented in file "Input data transformation".

After that hierarchical models are built which represent processes on two levels. Original data contains seven possible verdicts from the assessment system.  
On the first level model shows all tasks without differentiation based on verdicts. On the second level models for each task are built with all types of verdicts received. Model name contains the name of the miner is given in postfix: "heu" for heuristic or "ind" for inductive (i.e. "XXX_ind.pnml")
Altogether the analysis of event log, models built and algoritms of finding three different patterns of students' behavior are presented in file "Models visualization".

Together, the analysis of the converted event log and both level models will help answer the following questions:

1.	How do different process models contribute to the understanding and analysis of online assessment processes, and what are the advantages and limitations of each model in this context?
2.	How do hierarchical Petri nets address the limitations of traditional Petri nets in modeling online assessment processes?
3.	Which patterns in hierarchical Petri nets can be effectively utilized to analyze student behavior within individual assessment tasks?
4.	What algorithms can be developed to automatically detect patterns of student behavior in online assessment processes? What benefits can be obtained from their use compared to visual analysis of the model?

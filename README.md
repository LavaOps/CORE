# CORE

In order to use the notebooks to reproduce the results, the repository must be downloaded. The user must also be able to run ipynb files (a python notebook). For example, this can be done is Jupyter Lab or Jupyter notebook as well as Visual Studio Code. 

Dependencies

Notebooks reproducing COBRApy results require the following. 

(1) *COBRApy* version 0.25.0
The authors used CPLEX with an academic license for the solver. Solvers can be set or changed as shown below.

model.solver = 'cplex'

COBRApy can also use glpk (open source) or Gurobi (academic license available) solvers.

Notebooks reproducing ReFramed results require the following. 

(2) *ReFramed* version 1.2.1
The authors used CPLEX with an academic license for the solver. 

ReFramed can also use Gurobi. There is also an OptLang interface allowing for a larger selection of solvers. 

(3) *KBase* 
Link to the Narratives in KBase is below. 
https://narrative.kbase.us/narrative/160185


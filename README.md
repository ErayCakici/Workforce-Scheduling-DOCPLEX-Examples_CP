# Test__Workforce-Scheduling-DOCPLEX-Examples_CP

This repository provides constraint programming formulations for workforce (employee) scheduling problems. Employees can also be viewed as machines, and each of these problems can represent different instances of parallel machine scheduling. It is aimed to have special cases which are not already addressed in [machine scheduling examples repository](https://github.com/ErayCakici/Machine-Scheduling-DOCPLEX-Examples_CP) and not available explicitly on the internet. 

Optimization models are formulated in Python and solved with Cplex by using DOcplex Python Modeling API.

Problems addressed are: 
- [Employee scheduling to minimize latest completion time of tasks (a basic example)](https://github.com/ErayCakici/Test__Workforce-Scheduling-DOCPLEX-Examples_CP/blob/main/00_Basic.ipynb)
- [Employee scheduling with skillset requirements](https://github.com/ErayCakici/Test__Workforce-Scheduling-DOCPLEX-Examples_CP/blob/main/01_Skills.ipynb)
- [Employee scheduling with collaborative work](https://github.com/ErayCakici/Test__Workforce-Scheduling-DOCPLEX-Examples_CP/blob/main/02_Collaborative.ipynb)
- [Employee scheduling with time lags](https://github.com/ErayCakici/Test__Workforce-Scheduling-DOCPLEX-Examples_CP/blob/main/03_TimeLags.ipynb)
- [Employee scheduling with sequence dependent setup times (based on task types)](https://github.com/ErayCakici/Test__Workforce-Scheduling-DOCPLEX-Examples_CP/blob/main/04_SeqDep.ipynb)
- [Employee scheduling with breaks](https://github.com/ErayCakici/Test__Workforce-Scheduling-DOCPLEX-Examples_CP/blob/main/05_Breaks.ipynb)
- [Employee scheduling with allowed preemption](https://github.com/ErayCakici/Test__Workforce-Scheduling-DOCPLEX-Examples_CP/blob/main/06_Preemption.ipynb)

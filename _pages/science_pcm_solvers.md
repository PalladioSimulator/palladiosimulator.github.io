---
title:  Solvers, Analyses, and Simulations
layout: single
permalink: /science/palladio_component_model/solvers/
classes: wide
---

The are plenty of solvers, analyses, and simulations available for the Palladio Component Model (PCM). Depending on the intended quality dimension (i.e. performance, reliability, and costs) and the targeted precision, time and resource consumption, and acceptable overhead, different solvers can be used. All solvers (including analyes and simulations) take instances of the PCM meta-model as input and then derive [quality metrics](/tools/quality_dimensions/) (e.g. response time, throughput) from that.

Currently available solvers, analyses, and simulation approaches include (2015/04):

| Name                  | Class                                 | Quality dimensions            | Comment                   |
|-----------------------|---------------------------------------|-------------------------------|---------------------------|
SimuCom                 | process and event-based simulation    | performance, reliability      | default simulator, most powerful |
LQN Solver (LQNS)       | analytical approach                   | performance                   | fast numeric approximation |
Reliabiliy Solvers      | analytical approach                   | reliability                   | fast reliability analyses |
EventSim                | event-based simulation                | performance                   | simulation approach performing faster simulations in some areas than SimuCom; able to better handle very high concurrency |
QPNSolver               | queuing network simulation            | performance                   | queuing Petri nets simulator |
[PerOpteryx](/tools/peropteryx)        | analysis                              | costs                         | included feature of PerOpteryx |
ProtoCom                | load generator, real code execution   | performance, resource workload | workload for actual software and hardware stack |
Prototype generator     | code stub generator                   | coding, architecture generation | starting point for implementations of architectures described in PCM; speeds up development by POJO generation. |
[SimuLizar](https://sdqweb.ipd.kit.edu/wiki/SimuLizar)         | simulation                            | performance                   | analyzing self-adaptive systems, such as cloud computing systems, at design-time |
[LINE](http://line-solver.sourceforge.net/)              |analysis                               | performance                   | scalable solver for queueing network models based on ordinary differential equations; calculates percentiles of response times (e.g. for SLA assessment); includes uncertainties about operational environment | 
Stochastic regular expressions (StoExSolver) | analysis         | performance                   | fast calculation of distribution function for one user |
[e-Motions Transformation](http://atenea.lcc.uma.es/index.php/Main_Page/Resources/E-motions/Palladio) | analysis                       | performance, real-time        | simulation and formal analysis of real-time systems |
(discontinued) LQN Simulation | simulation                      | performance                   | simulation based solver for queuing networks (available through PCM Solver) 

Further information on PCM solvers is available in the PCM developer wiki: [Palladio Solvers and Simulation](https://sdq.kastel.kit.edu/wiki/PCM_AddOns).

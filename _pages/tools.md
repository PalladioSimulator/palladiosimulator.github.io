---
title: Palladio Tools
layout: single
permalink: /tools
classes: wide
---

We have implemented an integrated modelling environment (called Palladio-Bench) based on the Eclipse IDE. It enables developers to create Palladio Component Model (PCM) instances with graphical editors and derive performance, reliability, maintainabilty, and cost metrics from the models using analytical techniques and simulation. The Palladio Component Model (PCM) is implemented using the Eclipse Modeling Framework ([EMF](http://www.eclipse.org/modeling/emf/)).

Using the Palladio-Bench, you model PCM instances, simulate models, view simulation results, and derive software design optimisations.
See our [screenshots](/tools/screenshots) for impressions.

The best way for getting started with the Palladio-Bench is looking through the screencasts and tutorials provided on this page.

Did you know? Palladio is an official [Sourceforge project](http://palladio.sourceforge.net/).

## Development Tools
The open source development of the Palladio tooling is supported by the following software-products/-vendors:
![JProfiler](/assets/images/tools/support_jprofiler.png) ![Atlassian](/assets/images/tools/support_atlassian.png)

[![Download](/assets/images/tools/download.png) Download](/tools/download/)



## Palladio Features

Palladio comprises tons of exciting unique features which make the simulation of software architectures described in the Palladio Component Model (PCM) an interactive exploration of software design. Various analysers and the support of multiple quality dimensions are outstanding features of Palladio which help in the analysis and optimisation of software design at the architecture level. The Palladio-Bench integrates modelling, simulation/analysis, and result viewing in a single software tool.

Analyse the relevant architecture-level design decisions, capture the as-is state, identify problems, and derive optimisations. Palladio supports all typical analysis scenarios.

### Architecture Modelling

- High-Quality and convenient [editors](/tools/screenshots/) and graphical editing of all architectural elements
    + Component types, interfaces
    + Architectural structure
    + Service specification
    + Hardware resources and deployment 
- [Four quality dimensions](/tools/quality_dimensions/): Palladio offers analysis of performance, reliability, maintainabiltiy, and costs

### Model Solvers

- 1-click-solving of models
- Palladio features a simulation. Get forecasts faster than by "trying".
- Our [solvers](https://sdqweb.ipd.kit.edu/wiki/Palladio_Solvers_and_Simulation) support analytical solution
    + Find important Qos (Quality of Service) behaviour jumps for your application.
    + Find critical contention levels – when will your hardware be in an overload situation.
- Large variety of solvers
    + Simulation (event-based)
    + Analysis
    + PCM Solver (Markovian analysis)

All [software and editors](/tools/download) are free!

### Using Palladio you can ...

- ...predict / forecast before implementing software or new parts of a software.
- ...find critical bottlenecks.
- ...answer [sizing / scalability / relocation](/analysis) questions without buying hardware.
- ...estimate results of a change in the usage profile
- ...show the performance impact of extensions to legacy software
- ...play "What if? Games" with your software without implementing any line of code.


## Add-Ons

Palladio is easily extendable. A selection of readily available extensions:

- [SoMoX](/tools/somox/) - the SOftware MOdel eXtractor is a reverse engineering approach for Palladio models. Palladio models are created from C, C++, Java, and Delphi source code.

- [PerOpteryx](/tools/peropteryx/) is automated design space exploration and model optimisation for Palladio models. Based on given input Palladio models, a description of the design space (e.g. maximum allowed costs and servers), the input Model is optimised.


Further extension are [currently under development](/science).


## License

The Palladio Component Model (PCM) is licensed under the Eclipse Public License (EPL), Version 1.0.

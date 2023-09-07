---
title:  Palladio Component Model (PCM) 
layout: single
permalink: /science/palladio_component_model/
classes: wide
---

The Palladio Component Model (PCM) is one of the core assets of the Palladio approach. It is designed to enable early performance, reliability, maintainability, and cost predictions for software architectures and is aligned with a component-based software development process. The PCM is implemented using the Eclipse Modeling Framework ([EMF](http://www.eclipse.org/modeling/emf/)).

The Palladio Component Model captures the software architecture with respect to static structure, behaviour, deployment/allocation, resource environment/execution environment, and usage profile. In the Palladio Component Model, software is described in terms of components, connectors, interfaces, individual service behaviour models (so-called Service Effect Specifications, SEFF), servers, middleware, virtual machines, network, the allocation of components and servers, models of the user interaction with the system, etc. Overall, the PCM captures multiple views of software systems including elements which affect the extra-functional properties (e.g. performance, reliability) of software systems.

Due to a high degree of parameterisation, instances of the Palladio Component Model are largely reusable. If for example the usage profile of a software system changes, only the usage profile model needs to be adapted. All component specifications etc. can be reused. During analyses, Palladio automatically accounts for the impact of the changed usage profile.

![Model, Roles, Relations](/assets/images/science/pcm_palladio-model-roles-relations.png)

We have implemented an integrated modelling environment (called [Palladio-Bench](/tools)) based on the Eclipse Rich Client Plattform. It enables developers to create PCM model instances with graphical editors and conduct [analyses](/analysis) (using [analytical techniques and simulation](/science/palladio_component_model/solvers/)), resulting in for example performance and reliability metrics from the PCM models.

![Submodels, Analyses](/assets/images/science/pcm_palladio-sub-models-analyses.png)

Selected papers:

- [Overview of the Palladio Component Model](/assets/files/Introduction-Chapter-PCM.pdf) (28 pages, PDF): Palladio introduction paper
- Technical Report (203 pages, PDF): Description of the PCM meta-model
- Further literature and documentation is listed on the [Literature and Documentation](/science/#scientific-literature-and-documentation) page.
- A [classification of Palladio including the component model, meta-model and analyses](/science/palladio_component_model/classification/) from a scientific perspective

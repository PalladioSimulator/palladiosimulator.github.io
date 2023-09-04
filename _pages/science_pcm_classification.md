---
title:  Classification of the Palladio Component Model (PCM)
layout: single
permalink: /science/palladio_component_model/classification/
classes: wide
---

The following listing helps to classify the [Palladio Component Model (PCM)](/science/palladio_component_model/) which is underlying the Palladio approach. In case you are preparing a taxonomy or try to identify whether specific features are supported by the PCM, this page assists your work.

- Supported quality dimensions
    + Performance
    + Reliability
    + Costs
    + Maintainability 
- Meta-Meta-Model: UML2 and ECORE representation are available
- Meta-Model: Own meta-model (i.e. no UML profile); the meta-modell posseses execution semantics; OCL constraints ensure model integrity
- Meta-Model implementation: Eclipse EMF and Java
- Interface model: Corba IDL-like
- Supported compositions
    + Vertical: Composition by component assembly
    + Horizontal: Composition by component allocation
    + Hierarchical / nesting: Component encapsulation by composite components, subsystems, and systems 
- Component modelling
    + Three different component types (Provided Component Type, Complete Component Type, Implementation Component Type)
    + Two different component realisations (Composite Components, Basic Components)
    + Multiple type and instance levels (assembly, allocation, usage) 
- Model partitioning
    + Component repository: Definition of components and interfaces
    + System: Definition of component assembly
    + Execution environment: Definiton of hardware nodes and network
    + Component Allocation: Definition of how component are deployed on hardware nodes 
- Supported developer roles (can interact independently)
    + Component developer
    + Software architect
    + Component deployer
    + QoS analyst 
- Behaviour Model (describes single provided services of a component)
    + Internal and external actions
    + Sequences
    + Alternatives (probabilistic + guard conditions)
    + Loops (probabilistic + guard conditions)
    + Concurrency support: Fork / join / barrier
    + Semaphores 
- Interaction
    + Request / reponse (call / return, synchronous)
    + Event-based communication (asynchronous)
- Parameterized component dimensions (i.e. dimension can vary for a readily defined component type)
    + deployment / allocation
    + usage
    + assembly
    + implementation 
- Stochastic Expression language for expressing parameterised control and data flow
    + Constants
    + Distributions
    + Mathematic calculations
    + Conditions
    + Equality and inequality checks 
- Supported states
    + Request-based (for each invocation of a provided service of a component)
        * Behaviour model state (which behaviour steps is currently executed)
        * Parameter values and paramter propagation per service request
        * Local variables 
    + Allocation-based (component configuration parameters per component instance)
    + During analysis: Contention effects / blocking
    + Further state is automatically derived from allocation, assembly, and usage of components (e.g. how a component is allocated)
    + Interface protocols (mandatory orders for calling component services of an interface): Supported but not implemented 

## Classification of the Palladio Component Model Analyses Approaches

- Analysis output
    + Performance: General distribution functions
    + Reliability: Mean value
    + Costs: Sum of component costs (e.g. development costs, procurement costs or total cost of ownership) and hardware costs (e.g. procurement costs, operating costs or total cost of ownership)
    + Maintainability: Expected maintainability costs 

## Special Features

- The PCM accounts for the performance impact of exchangeable middlewares, e.g. application servers ("performance completion")
- Derivation of service level agreements (SLA) from analysis results 

## Extended Support

- Java stub generation from the PCM model
- EJB stub generation from the PCM model
- Performance prototype generation (puts load on real hardware as specified in the model) 

*Please note: The classification of the Palladio Component Model given in Crnković, I.; Sentilles, S.; Vulgarakis, A.; Chaudron, M. R V, "A Classification Framework for Software Component Models," Software Engineering, IEEE Transactions on , vol.37, no.5, pp.593-615, Sept.-Oct. 2011, doi: [10.1109/TSE.2010.83](http://dx.doi.org/10.1109/TSE.2010.83) is partially wrong. Please refer to the above classification.*

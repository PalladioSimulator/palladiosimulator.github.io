---
title: Software Architecture Optimization 
layout: single
permalink: /consulting/architecture_optimization
classes: wide
---

When existing software architecture provide insufficient Quality of Service (QoS) properties like throughput, response time or availability, the existing software architecture has to be improved. Growth scenarios raise further QoS-challenges for existings software systems which might have not been initially designed for challending QoS requirements.

Palladio supports the optimization of existing software architectures. Palladio is also applicable to existing code and installations by combining runtime monitoring (aka application performance management and monitoring) with software design-based architecture optimizations.


## Case Study: ABB high performance service and maintenance data repository

How to reach a performance goal of ten times the initial performance for a given software system? How to derive a stable migration path from the current system architecture to one which supports the performance goals? How to be sure that the imagined changed software architecture will reach performance goals?

[ABB](http://www.abb.com/) uses Palladio in its software performance engineering activities for the ABB Remote Diagnostic Solutions (RDS, a high performance service and maintenance data repository which collects diagnostics data from installed robots).

For the RDS system, ABB combined [Compuware dynaTrace](http://www.compuware.com/application-performance-management/dynatrace-enterprise.html) for monitoring activities with a subsequent architecture-level performance analysis and optimisation based on [Palladio](http://www.palladio-simulator.com/home/) and a final automated design space exploration using [PerOpteryx](/tools/peropteryx).

ABB could improve system performance (focus: throughput) for a given hardware setup up to two times using low-level performance analyses based on dynaTrace data and code inspection. To reach the performance goal of at least ten times the initial performance, subsequent architecture-level performance optimisation were required. Ultimately, ABB could improve the system design using Palladio to reach the challenging performance goal of 10x improved performance.

Parts of the experiences and findings are summarised in a recent paper. The paper also includes the images depicted on the right hand side: 

*Thijmen de Gooijer, Anton Jansen, Heiko Koziolek, and Anne Koziolek. An industrial case study of performance and cost design space exploration. In Proc. 3rd Int. Conf. on Performance Engineering (ICPE'12), pages 205-216. ACM, April 2012.* \[[bib](http://www.koziolek.de/bibtex/2012_bib.html#Gooijer2012) \| [DOI](http://dx.doi.org/10.1145/2188286.2188319) \| [PDF](http://www.koziolek.de/docs/Gooijer2012-ICPE-preprint.pdf)\]

## Further references

Overview on further [reference projects and industrial partners](/consulting/references).

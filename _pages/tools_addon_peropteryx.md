---
title: "Addon: PerOpteryx"
layout: single
permalink: /tools/peropteryx/
---

**PerOpteryx** is automated design optimisation for Palladio. PerOpteryx is the name for a set of [Eclipse](http://en.wikipedia.org/wiki/Eclipse_%28software%29) plugins for the Palladio-Bench to automatically improve Palladio Component Model instances for performance, reliability, and cost properties. The approach is tailored to assists software architects in deriving and identifying optimal design decisions.

PerOpteryx generates a number of (Pareto) optimal design alternatives which are then proposed to the software architect. The software architect can then further refine those design alternatives to best fit the requirements of a software development project.

Due to the strong automation, dozenz to hundreds of design alternatives can be automatically explored. Only the best design alternatives are proposed to the software architect.

## Advantages

- Saved time for the software architect
- Automated exploration of very large design spaces
- Proposal of hard to manually identify design alternatives

## Steps of PerOpteryx

1. Initial Palladio model as input (standard Palladio models which are no further optimised)
2. Define constraints and set design space dimensions (e.g. maximum costs, available components)
3. Run PerOpteryx
4. Select a design alternative from the proposed (Pareto) optimal candidates (e.g. from one with optimal costs, one with optimal performance, 5. one with average costs and performance)
6. Refine the selected candidate (e.g. adapt cache size or thread pool size)
7. Implement the selected candidate

[More information on PerOpteryx design optimisation](http://sdqweb.ipd.kit.edu/wiki/PerOpteryx)

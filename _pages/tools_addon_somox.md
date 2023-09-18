---
title: "Addon: SoMoX"
layout: single
permalink: /tools/somox/
---

**SoMoX** reverse engineering SoMoX extracts Palladio Component Model instances from source code

SoMoX reverse engineers instances of the Palladio Component Model (PCM) from C, C++, Java, and Delphi source code. The reverse engineering supports is suitable to speed up the creation process of precise Palladio models for existing software systems.

The SoMoX component extraction supports basic components, composite structures, interfaces, ports, as well as connectors. The extracted models are suitable to improve understanding of existing software system and enable subsequent [quality analyses](/analysis). Analyses for software performance, reliability, and maintenance are executed by Palladio.

SoMoX extraction is based on the evaluation of multiple source code metrics. The extraction can be guided by metric settings which allow the adaptation of SoMoX to the specific component definitions and needs of individual projects. Currently, SoMoX supports source code of the languages C, C++,  Java and, Delphi. However, its general source code model can be easily extended to further programming languages. SoMoX has been developed within the context of the EU project Q-ImPrESS.

## Advantages

- Automated reverse engineering of Palladio models
- Reduced effort for the creation of Palladio models
- Base for subsequent [Palladio analyses](/analysis)
- Suitable for planning the [extension of legacy software systems](/analysis/extension/) with respect to QoS (Quality of Service)

## Results of reverse engineering

- Components: Basic and composite components
- Component interface and service signatures, ports (roles)
- Connectors: Assembly and delegation connectors
- Behaviour model (SEFF)

[Beagle](http://sdqweb.ipd.kit.edu/wiki/Beagle) is the complementary reverse engineering approach for parametric dependencies of behaviour models (SEFF).

[More information on SoMoX](https://sdqweb.ipd.kit.edu/wiki/SoMoX)

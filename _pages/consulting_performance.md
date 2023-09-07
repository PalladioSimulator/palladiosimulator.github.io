---
title: Performance Anomalies Detection and Monitoring
layout: single
permalink: /consulting/performance/
classes: wide
---

Is observed performance degradation a real performance anomaly (e.g. software failure) or an expected overload situation which is caused by many concurrent requests? Answering this question is difficult due to the complexity of performance behaviour in real software systems.

Palladio provides a way to differentiate between benign performance degradation and performance anomlies which are caused by unwanted user interaction, software errors, and hardware problems. Palladio models can be used at run time to compare actual performance behaviour and expected (predicted) behaviour for varying workload situations. Since the comparison between predicted and actual performance behaviour can be used for all workload situations, deviations can be detected at early (i.e. non-overload) stages.

Detected and classified performance deviations can initiate warn triggers for real anomalies even before actual performance break down. This avoids false alarms and creates sufficient time buffers for reacting to performance changes.

## Case Study: 1&1 E-Mail System

The e-mail system operated by the 1&1 Internet AG, which is one of Europe's largest e-mail providers, is the basis of several national and international e-mail platforms like GMX, web.de, mail.com and india.com. The system comprises more than 2,000 servers and provides services for more than 40 million users in Germany alone. In a project with the 1&1 mail department in Karlsruhe, we applied the Palladio to 1&1’s mail system with the aim to evaluate the applicability of the Palladio to such very large and distributed systems.

The results show that Palladio is able to predict the resource utilization on the different servers with high accuracy. Compared to the setup of an equivalent test system to analyse different load situations, the modelling effort is negligible. Additionally, the results of the project helped to identify potential performance improvements that are planned to be integrated within a next update cycle. The high accuracy of the predictions allows integrating the results into a workload-aware runtime performance monitoring approach.

Read more in our paper presented at the 10th Working IEEE/IFIP Conference on Software Architecture 2012 (WICSA’12): Christoph Rathfelder, Stefan Becker, Klaus Krogmann, and Ralf Reussner. Workload-aware system monitoring using performance predictions applied to a large-scale e-mail system. In Proceedings of the Joint 10th Working IEEE/IFIP Conference on Software Architecture (WICSA) & 6th European Conference on Software Architecture (ECSA), Helsinki, Finland, 2012. (to appear) \[[bib](http://sdqweb.ipd.kit.edu/publications/inproceedings_rathfelder_bib.html#rathfelder2012a)\].


## Further references

Overview on further [reference projects and industrial partners](/consulting/references).

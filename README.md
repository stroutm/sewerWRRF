## Investigating bidirectional impacts between sewer and WRRF system controls and decisions
<img align="left" src="fig_citysewer_sensingcontrol.png" width="250">

The coordinated control of sewer assets presents the opportunity to begin viewing the sewer system as an extension of the downstream water resource recovery facility (WRRF, formerly known as wastewater treatment plants). With this potential, inflow conditions will be shaped to benefit treatment performance and water quality; see an example of this in a previous [paper](https://doi.org/10.1039/C9EW00882A) and its corresponding [GitHub repository](https://github.com/stroutm/LBCsewer). This is particularly critical for minimizing the discharge of nutrients, such as nitrogen and phosphorus, which are energy- and cost-intensive to treat and are significant water pollutants.

This repo interfaces Sumo ([Dynamita](http://www.dynamita.com/)), a wastewater treatment process simulator, with Python to simulate and evaluate the impacts of sewer control on downstream treatment processes, as well as elucidate coordination opportunities for preemptive, rather than reactive, system-wide control strategies.

More than just enabling more efficient treatment performance, this work aims to show how the interaction of sewer and WRRF dynamics stands to change how operational decisions are made in terms of system resilience and the perception of risk in control actions.

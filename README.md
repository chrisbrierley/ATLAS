# IPCC-Atlas

#### Code for reproducing some of the products of the AR6 WGI Interactive Atlas (First Order Draft)

The **accessibility and reproducibility of scientific results** is a major concern in all scientific disciplines. During the design and development of the Interactive Atlas, special attention has been paid to these problems in order to ensure the **transparency of the products feeding the Interactive Atlas** (which will be all publicly available). Accessibility will be established **in collaboration with the IPCC Data Distribution Centre** (based on curated IPCC-DDC datasets). The Atlas products are generated using **free software community tools**, in particular [R](https://www.r-project.org) building on the [**climate4R** framework](https://github.com/SantanderMetGroup/climate4R) for data post-processing (regridding, aggregation, bias adjustment, etc.) and evaluation and quality control (when applicable). **Provenance metadata** information will be provided for all products using the [**METACLIP**](http://www.metaclip.org) RDF-based framework (building on the [metaclipR](https://github.com/metaclip/metaclipR) package for the climate4R framework).

This repository is a start for the reproducibility activities of the IPCC WGI Atlas, including **a first illustrative (Jupyter) notebook** with commented code for reproducing some of the figures of the Atlas regional synthesis. Editing and executing notebooks locally requires software installation and configuration (see the installation options with  [docker](https://github.com/SantanderMetGroup/climate4R/tree/master/docker) or [conda](https://github.com/SantanderMetGroup/climate4R/tree/master/conda)), therefore, the computing facility [**climate4R Hub (C4R hub)**](https://hub.ipcc.ifca.es) is provided as an additional alternative, allowing IPCC users to edit/run provided notebooks in a remote machine where all the software is pre-installed. C4R Hub builds on the R framework for statistical computing with a pre-installed version of the climate4R packages, allowing for transparent climate data access, collocation, post-processing (including bias correction) and visualization. Find instructions to start working with the C4R Hub in [IPCC-Atlas_hub_instructions.pdf](https://github.com/SantanderMetGroup/IPCC-Atlas/blob/master/IPCC-Atlas_hub_instructions.pdf) of this repository.

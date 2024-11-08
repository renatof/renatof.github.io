---
title: "FaaSr: R Package for Function-as-a-Service Cloud Computing"
collection: publications
permalink: /publication/joss_fassr_2024
excerpt: 'This paper overviews the FaaSr package software design and implementation'
date: 2024-11-01
venue: 'Journal of Open Source Software'
paperurl: 'https://doi.org/10.21105/joss.07027'
citation: 'Sungjae Park, Yun-Jung Ku, Nan Mu, Vahid Daneshmand, R. Quinn Thomas, Cayelan C. Carey, Renato J. Figueiredo, “FaaSr: R Package for Function-as-a-Service Cloud Computing”, Journal of Open Source Software, 9(103), 7027'
---

The FaaSr software makes it easy for scientists to execute computational workflows developed natively using the R programming language in Function-as-a-Service (FaaS) serverless cloud infrastructures and using S3 cloud object storage. A key objective of the software is to reduce barriers to entry to cloud computing for scientists in domains such as environmental sciences, where R is widely used. To this end, FaaSr is designed to hide complexities associated with using cloud Application Programming Interfaces (APIs) for different FaaS and S3 providers, and exposes to the end user a set of simple function interfaces to: 1) register and invoke FaaS functions, 2) compose functions to create workflow execution graphs, and 3) access cloud storage at run time. The software supports encapsulation of execution environments in Docker images that can be deployed reproducibly
across multiple providers: AWS Lambda, GitHub Actions, and OpenWhisk, where users are able to leverage a baseline image with the widely-used Rocker/Tidyverse runtime, as well as customize their execution environment if needed. FaaSr is available as a CRAN package to facilitate its installation in R environments.
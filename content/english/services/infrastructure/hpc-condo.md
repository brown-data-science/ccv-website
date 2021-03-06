---
title: "HPC Condo"
date: 2018-02-24T15:09:10-04:00
draft: false
lead: "Dedicated high-performance computing resources for researchers in the form of 'condos' on the University's main supercomputer, Oscar."
category: Computing
icon: server2
haas: true
extra:
  text: "Risk Classification: Level 2"
  link: "https://it.brown.edu/computing-policies/risk-classifications"
---


# Condo Model
CCV provides a mechanism for investigators to purchase equipment and add it as a "condo" (condominium). The purchased hardware is not reserved for the exclusive use of the purchaser; rather, it is placed in a general pool of nodes, and the purchaser is given high priority access to 1.25 times the number of purchased cores. For example, a researcher or lab purchasing hardware with 1000 CPU cores would actually receive a condo on [Oscar](services/infrastructure/oscar/) with 1250 CPU cores. 

Note that condo purchases are not limited to CPU-only nodes; GPU nodes can also be included as part of a condo. 

## Job Priority
The high priority guarantees that the purchaser's jobs will run prior to any subscription-based use, unless the purchaser is already using their limit of 1.25 times the number of cores purchased. Condo jobs are also not subject to the conventional wall clock limits of `Exploratory` or `Priority` accounts on Oscar.

## Processors and Memory
CCV standardizes processor and memory configurations for a period of roughly six months to a year in order to maintain a degree of homogeneity in the cluster. As an example, our current standard node CPU configuration is two-socket Intel Xeon Gold 6242 (16-core, 2.8GHz), with node memory of either 192GB or 384GB.

# Purchasing
Pricing is dependent on the size of the condo, and will be provided upon request. Please contact CCV at [support@ccv.brown.edu](mailto:support@ccv.brown.edu).
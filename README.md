# Simulate-Network-and-Cluster-Data
Simulation framework for network and clustered data with interference, including tools to construct networks/clusters, generate potential outcomes, and compute true causal effect


# NetClusterSim

`NetClusterSim` is an R package for simulating causal inference under interference in both clustered and network settings. The package provides tools to construct cluster and network structures, generate potential outcomes, define observed outcomes under treatment assignment, and compute true causal effects under user-specified treatment allocations.

## Features

The package includes functions for:

- building clustered data structures
- building network data structures from edge lists
- simulating potential outcomes under interference
- generating observed treatment and outcome data
- computing true causal effects, including direct, indirect, total, and overall effects

For clustered settings, the package includes functions to build cluster data, simulate cluster outcomes, and compute true causal effects from cluster-level potential outcomes. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3} :contentReference[oaicite:4]{index=4}

For network settings, the package includes functions to build a network from edge data, simulate network outcomes, and compute true causal effects from network potential outcomes. :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6} :contentReference[oaicite:7]{index=7}

## Installation

You can install the development version from GitHub with:

```r
# install.packages("devtools")
devtools::install_github("YOUR_USERNAME/NetClusterSim")






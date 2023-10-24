# Replication material for the paper entitled "Testing the Evolution of Feature Models with Specific Combinatorial Tests"

This repository contains the replication material for the paper entitled "Testing the Evolution of Feature Models with Specific Combinatorial Tests" and submitted to ICST 2024

## Repository structure

* [`featuremodels.specificity`](https://github.com/fmselab/ReplicationPackageICST2024/tree/main/featuremodels.specificity): the Eclipse project containing the SPECGEN and the BDDGEN generators, the interface to the other state-of-the-art generators and the code executing the experiments
  * [`experiments`](https://github.com/fmselab/ReplicationPackageICST2024/tree/main/featuremodels.specificity/experiments): it contains
    * [`specificity_analysis.ipynb`](https://github.com/fmselab/ReplicationPackageICST2024/blob/main/featuremodels.specificity/experiments/specificity_analysis.ipynb), the jupyter notebook we have used for executing the Wilcoxon-Signed Rank tests and for producing the box-plots we report into the paper
    * [`resultsSPECIFICITY.csv`](https://github.com/fmselab/ReplicationPackageICST2024/blob/main/featuremodels.specificity/experiments/resultsSPECIFICITY.csv), the output of the experiments
    * [`imgs`](https://github.com/fmselab/ReplicationPackageICST2024/tree/main/featuremodels.specificity/experiments/imgs), it contains the box-plot pictures

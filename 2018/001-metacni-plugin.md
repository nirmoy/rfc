 Title

| Field  | Value      |
|:-------|:-----------|
| Status | Draft      |
| Date   | 2018-10-29 |

## Introduction

### Problem description

Kubernetes currently supports only one cni plugin for all pods. There are many 
limitation in this approach.
 * Pods can have only one interface
 * It is not possible to levarage diffrent networking solutions like: DPDK, SR-IOV, openvSwitch
 * Different SDN.... 
### Proposed change
 * Allow multiple CNI support using meta-plugin
   as per [Kubernetes Network Custom Resource Definition De-facto Standard](https://docs.google.com/document/d/1Ny03h6IDVy_e_vmElOqR7UdTPAG_RNydhVE1Kx54kFQ/edit#) 
### Work flow
<p align="center">
   <img src="https://github.com/intel/multus-cni/blob/master/doc/images/workflow.png" width="1008" />
</p>

## Detailed RFC



### Proposed change (Detailed)

### Dependencies

### Concerns and Unresolved Questions


## Alternatives


## Revision History:

| Date       | Comment       |
|:-----------|:--------------|
| YYYY-MM-DD | Initial Draft |

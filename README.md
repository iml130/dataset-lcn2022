# Peer Discovery in Tree-Structured P2P Overlay Networks by Means of Connected Dominating Sets

This repository contains the dataset used for the paper [_"Peer Discovery in Tree-Structured P2P Overlay Networks by Means of Connected Dominating Sets"_](https://doi.org/10.1109/LCN53696.2022.9843678) published at the [IEEE 47th Conference on Local Computer Networks (LCN)](https://www.ieeelcn.org).
We refer to the paper for a full explanation of the methodology used for generating the dataset.

## Abstract

A Peer-to-Peer (P2P) network consists of a large number of nodes, where each node may have different capabilities and properties. 
Finding peers with specific capabilities and properties is challenging. 
Thus, we propose a practical solution to the problem of peer discovery, which is finding peers in the network according to a specified query.
We contribute a peer discovery for an m-ary tree-structured P2P network by utilizing a connected dominating set (CDS), a technique that is typically used in unstructured networks. 
Our approach of constructing the CDS requires no additional communication cost, while nodes can insert, update and remove data within O(1). 
Each node of the CDS – a dominating set node – maintains only a limited number of nodes. 
We confirm the properties of our proposed solution by using the ns-3 discrete-event simulator. 
This includes, besides the degree of decentralism of the peer discovery, also the heterogeneity of peers.

## Reading the dataset

The dataset is stored as a comma-separated values (CSV) file, using a semicolon (;) as a delimiter.
```csv
NumberOfNodes;Fanout2;Fanout4;Fanout8;Fanout16
1000;...
2000;
3000;
4000;
5000;
6000;
7000;
8000;
9000;
10000;
```


## Citation

If you to cite the paper or this dataset for your research, please include the following reference in any resulting publication:

```bibtex
@INPROCEEDINGS{9843678,
  author={Detzner, Peter and G&#x00F6;deke, Jana and Bondorf, Steffen},
  booktitle={2022 IEEE 47th Conference on Local Computer Networks (LCN)}, 
  title={Peer Discovery in Tree-Structured P2P Overlay Networks by Means of Connected Dominating Sets}, 
  year={2022},
  volume={},
  number={},
  pages={447-454},
  doi={10.1109/LCN53696.2022.9843678}}
```

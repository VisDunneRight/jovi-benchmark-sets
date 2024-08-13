# Autonomous System Network

Note: The 733-AS network is a subset of SNAP. We provide the link containing the original project, https://www.routeviews.org/routeviews/, and redirect to SNAP, https://snap.stanford.edu/data/as-733.html for the network data. In the dataset description they highlight how the graphs exhibit node and edge addition and deletion over time. 
Origin Notes: The data was originally part of the University of Oregon’s RouteViews project. It was then used by Jure Leskovec et al. and eventually stored in SNAP.
graph features handled: dynamic, generic
Graph features in papers: generic
Origin Paper: Preserving Minority Structures in Graph Sampling (https://www.notion.so/Preserving-Minority-Structures-in-Graph-Sampling-d0f9e612663d434e85599c402c9b700c?pvs=21), Graphs over Time: Densification Laws, Shrinking Diameters and Possible Explanations (https://www.notion.so/Graphs-over-Time-Densification-Laws-Shrinking-Diameters-and-Possible-Explanations-9b33c460755241c591e462c7326db101?pvs=21)
Originally found at: https://www.routeviews.org/routeviews/
https://snap.stanford.edu/data/as-733.html
https://github.com/csuvis/MCGS/blob/master/dataset/AS-733_edge.csv
Number of Graphs: 733
Appeared in years: 2021
Type of Collection: Subset of other collection
is it stored properly?: No
must be analyzed: No
In repo?: Yes
Related to Literature - Algorithm (1) (Dataset tag relations): Preserving Minority Structures in Graph Sampling (https://www.notion.so/Preserving-Minority-Structures-in-Graph-Sampling-cf062d6fa8f5484ab1190edd125f739f?pvs=21)
cleaned format?: No
duplicate?: No
link works?: Yes
Added in paper: No
Origin paper plaintext: Preserving Minority Structures in Graph Sampling, Graphs over Time: Densification Laws, Shrinking Diameters and Possible Explanations
Page id: 96d24eb9c7f94ab6a6b38e6a3af816ae
unavailable/skip: Yes
Cleaned ALL data: No
first look: Yes
Related to Literature - Algorithm (Dataset tag relations) 1: Preserving Minority Structures in Graph Sampling (../Benchmark%20sets%200cc6b5e454304aec98f3b59b1a720476/Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Preserving%20Minority%20Structures%20in%20Graph%20Sampling%202d52160d6ac04019aaf808496f7d4240.md)

# Body

### Descriptions from Literature

From “[Preserving Minority Structures in Graph Sampling](https://ieeexplore.ieee.org/document/9222065)”

> The AS-733 graph data set [48] is an autonomous systems network on the Internet with 6,474 nodes and 13,895 edges. The original graph and samples obtained by RDN, SST, MCGS are shown in Figure 5.
> 

From “[Graphs over time: densification laws, shrinking diameters and possible explanations](https://dl.acm.org/doi/10.1145/1081870.1081893)”

> The graph of routers comprising the Internet can be organized into sub-graphs called Autonomous Systems (AS). Each AS exchanges traffic flows with some neighbors (peers).
We can construct a communication network of who-talks-towhom from the BGP (Border Gateway Protocol) logs. We use the the Autonomous Systems (AS) dataset from [26]. The dataset contains 735 daily instances which span an interval of 785 days from November 8 1997 to January 2 2000.In contrast to citation networks, where nodes and edges only get added (not deleted) over time, the AS dataset also exhibits both the addition and deletion of the nodes and edges over time.
> 

### Example Figures

From “[Preserving Minority Structures in Graph Sampling](https://ieeexplore.ieee.org/document/9222065)”

![Untitled](Autonomous%20System%20Network%2096d24eb9c7f94ab6a6b38e6a3af816ae/Untitled.png)

**Fig. 5.** Case analysis of the AS-733 graph data set (a) and three samples generated by RDN (b), SST(c), and MCGS (d) with a sampling rate of 30%.

== STOP RENDERING ==

Possibly related to something like this:

[https://www.caida.org/catalog/datasets/ipv4_routed_24_topology_dataset/](https://www.caida.org/catalog/datasets/ipv4_routed_24_topology_dataset/)
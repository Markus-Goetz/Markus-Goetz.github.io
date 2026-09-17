---
title: "HPDBSCAN: Highly Parallel DBSCAN"
collection: publications
category: conferences
permalink: /publication/2015-01-01-hpdbscan-highly-parallel-dbscan
excerpt: 'We present HPDBSCAN, a highly parallel, distributed-memory implementation of the DBSCAN clustering algorithm that scales density-based clustering to large datasets on high-performance computing systems.'
date: 2015-01-01
venue: 'Proceedings of the Workshop on Machine Learning in High-Performance Computing Environments (MLHPC 15), pp. 1–10'
paperurl: 'https://doi.org/10.1145/2834892.2834894'
citation: 'Götz, M., Bodenstein, C., &amp; Riedel, M. (2015). &quot;HPDBSCAN: Highly Parallel DBSCAN.&quot; In: <i>Proceedings of the Workshop on Machine Learning in High-Performance Computing Environments (MLHPC 15)</i>, pp. 1–10.'
---

DBSCAN is a widely used density-based clustering algorithm, but its inherently sequential design limits scalability to large datasets. We introduce HPDBSCAN, a highly parallel, distributed-memory reformulation of DBSCAN that partitions the data across compute nodes while preserving the algorithm's clustering semantics. HPDBSCAN achieves substantial speedups over existing implementations, enabling density-based clustering of large-scale scientific datasets on modern HPC systems.

[Download paper here](https://doi.org/10.1145/2834892.2834894)

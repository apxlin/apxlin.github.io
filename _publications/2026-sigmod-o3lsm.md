---
title: "O3-LSM: Maximizing Disaggregated LSM Write Performance via Three-Layer Offloading"
collection: publications
category: conferences
permalink: /publication/2026-sigmod-o3lsm
excerpt: 'We design an LSM-based KV store leveraging Disaggregated Memory via RDMA to scale writes, achieving 4.5x higher write throughput and 76% lower P99 latency.'
date: 2026-01-01
venue: 'Proceedings of ACM Conference on Management of Data (SIGMOD)'
citation: '<b>Qi Lin</b>, Gangqi Huang, Te Guo, Chang Guo, Viraj Thakkar, Zichen Zhu, Jianguo Wang, Zhichao Cao. &quot;O3-LSM: Maximizing Disaggregated LSM Write Performance via Three-Layer Offloading.&quot; <i>Proceedings of ACM Conference on Management of Data (SIGMOD)</i>, 2026.'
---

We design an LSM-based KV store that leverages Disaggregated Memory (DM) via RDMA to scale writes, achieving 4.5x higher write throughput and 76% lower P99 latency. We build a DM-optimized memtable that extends the write buffer via remote memory and adds shard-level flush offloading to idle compute/memory nodes, increasing flush parallelism and accelerating L0 compaction. We also implement cache-enhanced read delegation, a local key-offset cache with RDMA-assisted remote access, delivering up to 5.2x faster point/range queries.

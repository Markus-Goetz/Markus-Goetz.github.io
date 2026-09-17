---
title: "Combining Domain and Tensor Parallelism to Train Multi-billion-parameter AI Weather Models"
collection: publications
category: conferences
permalink: /publication/2026-01-01-domain-tensor-parallelism-weather-models
excerpt: 'We introduce Jigsaw, a model parallelization scheme combining domain and tensor parallelism to train multi-billion-parameter AI weather models, eliminating memory redundancy and achieving state-of-the-art scaling on up to 256 GPUs.'
date: 2026-01-01
venue: 'Proceedings of the Platform for Advanced Scientific Computing Conference (PASC 26)'
paperurl: 'https://arxiv.org/abs/2507.05753'
citation: 'Kieckhefen, D., Götz, M., Heyen, L. H., Streit, A., &amp; Debus, C. (2026). &quot;Combining Domain and Tensor Parallelism to Train Multi-billion-parameter AI Weather Models.&quot; In: <i>Proceedings of the Platform for Advanced Scientific Computing Conference (PASC 26)</i>.'
---

Training AI weather foundation models at high spatial resolution and billion-parameter scale is bottlenecked by accelerator memory and I/O bandwidth. We introduce Jigsaw, a novel parallelization scheme that combines domain parallelism and tensor parallelism to eliminate memory redundancy during training. Applied to the WeatherMixer architecture, Jigsaw exceeds state-of-the-art performance in compute-communication-limited settings and achieves superscalar weak scaling in I/O-bandwidth-limited settings, scaling to 256 GPUs and multi-billion-parameter models.

[Download paper here](https://arxiv.org/abs/2507.05753)

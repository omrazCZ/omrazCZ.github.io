---
title: "BSc Research Project: Autotuning Geo-Distributed Systems"
collection: supervision
type: "BSc Thesis"
permalink: /supervision/2026-bsc-autotuning-distributed
venue: "TU Delft, EEMCS Faculty"
date: 2026-01-15
location: "Delft, Netherlands"
---

In this project I supervise 5 BSc students in implementing and evaluating different autotuning policies for geo-distributed systems. Each student focuses on one autotuning mechanism.

## Background and Motivation

Distributed and geo-distributed databases form the backbone of countless critical applications, from global e-commerce to real-time analytics. However, they come with great complexity: Which system component is the bottleneck? How can I make my system faster? Where can I save on resources and cost? This project offers an opportunity to dive into this challenge by implementing and experimenting with policies for automatic resource allocation and dynamic data movement.

The students build on top of existing systems such as Detock [1] or Styx [2]. Their policies draw inspiration from existing autotuning mechanisms, such as Dhalion [3], DS2 [4], Kubernetes HPA [5], Tuba [6], and PNUTS [7].

## Research Methodology

Each student implements and tests one of the autotuning policies following this research method:

1. Study existing autotuning systems' strategies
2. Profile the performance and identify bottlenecks of Detock and Styx
3. (For reinforcement learning policies) Collect training data from manual rescaling/data movement decisions
4. Design and implement a new policy
5. Test and evaluate performance improvement (throughput & latency) and cost savings

## Policies to Implement

- A control-based policy for automatic resource allocation
- A reinforcement learning-based policy for automatic resource allocation
- A time series forecasting policy for automatic resource allocation
- A control-based policy for dynamic data movement
- A reinforcement learning-based policy for dynamic data movement

## Students

1. Rares Popa - TU Delft
2. Mihai Nicolae - TU Delft
3. Arpad Jakab - TU Delft
4. Kevin Che - TU Delft
5. Frank Verkoren - TU Delft

*Final reports coming soon*

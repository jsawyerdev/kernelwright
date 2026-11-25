# Kernelwright

> Status: concept repository - future work

Evidence-driven diagnosis and optimisation of Linux infrastructure.

## Objective

Diagnose Linux performance bottlenecks and test proposed configuration changes in isolation before deployment.

## Proposed scope

- Collect kernel and application evidence
- Generate testable tuning hypotheses
- Benchmark changes in controlled environments
- Reject changes that do not improve declared objectives

## Technical direction

eBPF, perf, gVisor, QEMU, and statistical optimisation.

The technologies above are candidates, not commitments. Selection will follow evidence from the smallest useful prototype.

## Open questions

- What observable result would make the first prototype useful?
- Which assumptions need controlled experiments before implementation?
- What independent oracle can determine whether an experiment succeeded?
- What is the smallest reproducible dataset or workload?

## Repository status

This repository reserves the project identity and records the initial concept. It contains no production implementation, published roadmap, or stable API.

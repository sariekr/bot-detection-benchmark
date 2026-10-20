# Bot Detection Benchmark

An observational benchmark of anti-bot technologies found on websites in AIMultiple's scraping tests. It compares how frequently each technology appears in the sampled domains with the rate at which requests are blocked.

[Read the benchmark on AIMultiple](https://aimultiple.com/bot-detection-software).

The analysis joins measurements from e-commerce and general-web workloads. It reconciles overlapping domains and protection labels, then calculates block rates with equal weight per domain. This prevents domains with more sampled pages from dominating the comparison.

The published charts include vendors meeting a minimum domain-coverage threshold. Results include uncertainty estimates and distinguish a vendor's share of the sampled sites from its observed block rate.

The measured sites chose their own protection products and configurations. Differences in site difficulty, policies, and workloads can affect the observed rates. The results describe this sample and testing setup. They cannot isolate the causal effect of choosing one anti-bot product.

The benchmark implementation was developed for AIMultiple and belongs to AIMultiple. This repository is a documentation summary. Source code and benchmark datasets are not distributed here.

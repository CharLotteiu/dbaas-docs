---
title: Select Your Cluster Tier
summary: Learn how to select your cluster tier on TiDB Cloud.
---

# Select Your Cluster Tier

This document describes how to select your cluster tier on TiDB Cloud.

## Cluster Tier overview

When creating a cluster, you need to select a cluster tier, which determines the throughput and performance of your cluster. Different cluster tiers provide different TiDB and TiKV node instance types. Different tiers are provided for AWS and GCP.

> **Note:**
>
> You cannot change the selected tier after your cluster is created.

## AWS Tiers

| Cluster tier | Node | CPU | Memory | Storage | Scenario |
| :-- | :-- | :-- | :-- | :-- | :-- |
| t1.tiny | TiKV | 2 vCPU | 2 G | 50 G EBS | Testing or development |
| t1.tiny | TiDB | 2 vCPU | 2 G | / | Testing or development |
| t1.standard | TiKV | 8 vCPU | 61 G | 1900 G NVMe | Production |
| t1.standard | TiDB | 8 vCPU | 16 G | / | Production |

## GCP Tiers

| Cluster tier | Node | CPU | Memory | Storage | Scenario |
| :-- | :-- | :-- | :-- | :-- | :-- |
| t1.tiny | TiKV | 1 vCPU | 3 G | 50 G | Testing or development|
| t1.tiny | TiDB | 1 vCPU | 3 G | / | Testing or development|
| t1.standard | TiKV | 8 vCPU | 52 G | 1875 G | Production |
| t1.standard | TiDB | 8 vCPU | 30 G | / | Production |

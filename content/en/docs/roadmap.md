---
date: 2023-04-17
draft: false
lastmod: 2023-04-17
linktitle: Roadmap
menu:
  docs:
    parent: welcome
    weight: 2
title: Roadmap
toc: true
type: docs
---
This document defines a high level roadmap for Kuasar development.

The roadmap below outlines new features that will be added to Kuasar.

| Sandboxer      | Sandbox          | 2023 H1 | 2023 H2 | 2024 H1 |
|----------------|------------------|---------|---------|---------|
| **MicroVM**    | Cloud Hypervisor | ✓       |         |         |
|                | QEMU             | ✓       |         |         |
|                | StratoVirt       | ✓       |         |         |
|                | Firecracker      |         |         | ✓       |
| **App Kernel** | Quark            | ✓       |         |         |
|                | gVisor           |         |         | ✓       |
| **Wasm**       | WasmEdge         | ✓       |         |         |
|                | Wasmtime         |         | ✓       |         |
| **runC**       | runC             |         | ✓       |         |


## 2023 H1

+ Support parts of mainstream sandbox, i.e. Cloud Hypervisor, QEMU, StratoVirt, WasmEdge, Quark
+ Support connection of containerd and iSulad via Sandbox API

## 2023 H2

+ Support runC container
+ Support Wasmtime
+ Support DRA(Dynamic Resource Allocation) API
+ Support CDI(Container Device Interface) API
+ Start the process of donating projects to CNCF

## 2024

+ Support more sandboxes, i.e. gVisor, Firecracker
+ Support running in Arm64.
+ Develop a CLI tool for operation and maintenance.

## 2025

+ Enhance on image distribution.
+ Support eBPF observation.
+ TBD
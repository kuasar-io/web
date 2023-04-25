---
authors:
- Kuasar Admin
categories:
- news
- Wasmedge
- openEuler
date: 2023-04-25
draft: false
lastmod: 2023-04-25
summary: Jointly initiated by HuaweiCloud, Agricultural Bank of China, WasmEdge and openEuler
tags:
- Kuasar
- Sandbox
- demo vedio
- wasmedge
- quark
- cloud-hypervisor
- node
title: Kuasar is officially open source on KubeCon + CloudNativeCon Europe 2023
---

# Jointly initiated by HuaweiCloud, Agricultural Bank of China, WasmEdge and openEuler

Amsterdam, Netherlands - April 21, 2023: On the morning of April 21st, at KubeCon + CloudNativeCon Europe 2023 held in Amsterdam, the cloud-native multi-sandbox container runtime Kuasar, jointly initiated by Huawei Cloud, Agricultural Bank of China, CNCF project WasmEdge, and openEuler community, was officially announced as open source (project address: https://github.com/kuasar-io/kuasar).

![kuasar-twitters](/img/blog/kuasar-joint-opensource/kuasar-twitters.png)

After the release of Kuasar, Chris Aniszczyk, CTO of CNCF, tweeted expressing his strong anticipation for the sandbox interface of Kuasar. CNCF official ambassador, James Spurin, also expressed his surprise and delight in Kuasar. The Kuasar project plans to be donated to CNCF to promote the development of cloud-native technology.

## Introduction to Kuasar

With the deepening of enterprise digital transformation, businesses are increasingly focusing on cloud-based innovation and lean operations, which has put higher demands on cloud-native technologies with the concept of "deep cloudification". To meet the demands of enterprises in cloud-native scenarios, various container isolation technologies have emerged in the industry, collectively referred to as "sandboxes." These include kernel-based native container sandboxes, microVM sandboxes based on lightweight virtualization technology, App Kernel sandboxes based on process-level virtualization, and emerging WebAssembly sandboxes. However, in the actual production process, the adoption of cloud-native sandbox technologies still faces the following challenges:

1. Higher demands from various cloud-native scenarios for sandboxes: Each sandbox technology has its advantages and disadvantages, and a single sandbox cannot simultaneously meet the multi-dimensional requirements of cloud-based businesses for security isolation, high-speed low-noise, and standard universality. How to achieve full coverage of cloud-native business scenarios has become an increasingly common challenge for enterprises.

2. Support for multiple sandboxes brings a significant increase in operation and maintenance pressure: The current implementation of sandbox technologies in the industry lacks a unified development framework for container runtimes. Therefore, there are differences in critical logs, important events, sandbox management logic, etc. when adopting different sandboxes. The introduction of new sandboxes can dramatically increase operation and maintenance pressure.

Kuasar leverages emerging sandbox interfaces and combines years of enterprise production experience with careful consideration of sandbox technology development. It provides support for multiple mainstream sandbox technologies, while retaining traditional container runtime features. By fully Rustifying and optimizing the management model and framework, Kuasar reduces management overhead and simplifies call chains. Moreover, Kuasar can flexibly expand support for various sandbox technologies to achieve full coverage of cloud-native business scenarios. Kuasar also supports the deployment of multiple secure sandboxes on a single node, enabling users to fully utilize node resources, reduce costs, and increase efficiency, providing a more secure and efficient sandbox solution for users.

![kuasar-overview](/img/blog/kuasar-joint-opensource/kuasar-overview.png)

## Eco-cooperation

The Kuasar project combines the technical accumulation and production practices of enterprises in the field of container runtime, as well as the cutting-edge exploration and development insights of the open source community in the sandbox isolation technology. This can provide detailed and effective practical guidance and help for enterprises and developers. By using Kuasar, enterprises and developers can break through the sandbox barriers at the cluster level, build a multi-sandbox container resource pool that is easy to operate, secure, efficient and low-noise, and meet the demands of container runtime for cloud-native business in all scenarios.

"Kuasar's open source will provide developers with more choices and support, and bring users more efficient, comprehensive, and flexible cloud-native container solutions."


—— Bill Ren, Huawei Chief Open Source Liaison Office

"Kuasar can seamlessly schedule multiple secure application containers, including WasmEdge. This is the solution that WasmEdge users, especially developers building microservices, edge applications, and AI big model applications, have been looking for."


—— Michael Yuan, Founder of WasmEdge Project

"OpenEuler is an all-scenario operating system. However, cloud, edge, and device have differentiated requirements for container infrastructure. Kuasar innovatively supports hybrid deployment of multiple sandboxes and interconnection of different ecosystems, meeting the requirements of diversified scenarios and helping OpenEuler partners achieve flexible and diversified container-based bases."


—— Hu Xinwei, Chairman of the OpenEuler Technical Committee

## Future development

Currently, at the southbound sandbox level, Kuasar already supports multiple mainstream security sandboxes including Cloud-Hypervisor (MicroVM class), WasmEdge (Wasm class), StratoVirt (MicroVM class), and Quark (App Kernel). Kuasar is in deep cooperation with the openEuler and WasmEdge communities, and expects to collaborate with more sandbox projects or communities to continuously improve its support for various mainstream sandbox technologies.

At the northbound interface level, Kuasar is jointly building the latest sandbox interface standard with the industry's mainstream container runtime, containerd. It has been added to the version roadmap of containerd v2.0. In addition, the lightweight container engine iSulad project of the openEuler community has already completed integration with the Kuasar project.

Looking to the future, as an open and scalable multi-sandbox container runtime, Kuasar will leverage the advantages of sandbox interfaces, embrace the latest management interfaces such as Dynamic Resource Allocation (DRA) and Container Device Interface (CDI), and provide more secure, efficient, and convenient container solutions for cloud-native scenarios, providing more comprehensive protection for cloud-native applications.

Welcome to follow our twitter：https://twitter.com/Kuasar_io
---
title: VNet Injection in Azure Chaos Studio
description: Understand how to control resource onboarding in Azure Chaos Studio by using targets and capabilities.
author: johnkemnetz
ms.author: johnkem
ms.service: chaos-studio
ms.topic: conceptual
ms.date: 10/10/2022
---

# Using VNet Injection in Azure Chaos Studio
VNet injection allows an RP to inject containerized workloads into a customer’s VNet. It allows for both ingress and egress traffic between the injected container
and the customer’s resources in the VNet. This means that resources without public internet access can be accessed via a private IP address on the VNet. 

Using VNet Injection for Chaos Studio enables you to:

- Secure your Web App by using  the Private Endpoint, eliminating public exposure.
- Avoid any data exfiltration from your virtual network.

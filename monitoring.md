---
title: Azure Monitoring and Observability Configuration
description: Prescriptive Azure Monitoring and Observability Configuration
author: William Darnell
ms.author: wdthecloudforge
ms.date: 06/20/2022
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: general
ms.custom: internal, operating-model
---

# Azure Monitoring and Observability Configuration

Azure provides cloud-based tools to allow you to monitor across all levels of your software stack and also the underlying compute, storage and networking components provided by Azure itself. 
The issue every business faces is understanding what services and solutions deliver end-to-end visibility to ensure quick resolution of anomolies and ensure performance and availability are maintained within SLAs. Moreover, in addition to the Technology focus for monitoring we need to establish a baseline for both People and Process.

## Get Started

The Microsoft Cloud Adoption Framework for Azure is a full lifecycle framework that enables cloud architects, IT professionals, and business decision makers to achieve their cloud adoption goals. It provides best practices, documentation, and tools that help you create and implement business and technology strategies for the cloud.

Within the Cloud Adoption Framework is existing documentation that details how you should formulate a strategy. It also covers how you begin to define a monitoring strategy.

https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/strategy/monitoring-strategy

https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/manage/monitor/

## Cloud Operations

Cloud operations: A function within the centralized technology organization, this operations function manages the health and operations of the technology portfolio. It's their responsibility to ensure the process runs smoothly, that each adjacent role in the process has the necessary tools, and that each of the subsequent roles is held accountable for expectations of this process.




We're trying to answer 2 questions here:
1. Who are the people involved? (the actors)
2. What do they need?


The Actors
This doc : https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/organize/cloud-operations 
states that cloud ops function can be provided by many folks.

This may be different depending on the operating model type as defined here : <operating model link from CAF READY>
as it may be a DevOps team rather than an MSP that provides operations.
  
  
What do they need?  
Additionally, if we overlay the Monitoring stack (Azure Monitor Overview doclink) we start to get a feel for the 
  types of information that is required by an operations function.






## Next steps

TBD
  
Who - cares/responds to alerts
What - which alerts
How - which tools
Optimisation - review & improve

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

## Get Started with a strategy

The Microsoft Cloud Adoption Framework for Azure is a full lifecycle framework that enables cloud architects, IT professionals, and business decision makers to achieve their cloud adoption goals. It provides best practices, documentation, and tools that help you create and implement business and technology strategies for the cloud.

Within the Cloud Adoption Framework is existing documentation that details how you should formulate a monitoring strategy:

https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/strategy/monitoring-strategy


## Organising your teams

Depending on the size of your organisation and your cloud maturity there are several options on how you may handle cloud monitoring. 

Again, the Cloud Adoption Framework has some guidance on organisational alignment and how you begin to move your teams towards delivering cloud functions.

https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/organize/organization-structures

https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/organize/raci-alignment

If you are new to the cloud you want to get to a position where you at least implement an organisational MVP. This is where you have one or more Cloud Adoption teams that are deploying resources held to account by a Cloud Governance team. 
As you'll see from the links above, the responsibility for monitoring is split between both teams: platform operations are handled by the Governance team and solution operations are handled by the Cloud Adoption teams.

talk about how, with the MVP, only 2 teams so have to wear multiple hats.
According to RACI doc (give link), we are looking at Governance team assuming the Cloud Platform function and CLoud Adoption teams becoming accountable for cloud operations.

quote the deliverables of each team :... 

As you grow in maturity you may wish to move towards a more mature enterprise scale organisational model and hence we would see the introduction of Cloud Operations and Cloud Platform teams.

## Defining your monitoring(?)

https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/manage/monitor/

https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/manage/monitor/cloud-models-monitor-overview

The goal of this guide is to provide a detailed reference to help enterprise IT managers, business decision makers, application architects, and application developers understand:

Azure monitoring platforms, with an overview and comparison of their capabilities.
The best-fit solution for monitoring hybrid, private, and Azure native workloads.
The recommended end-to-end monitoring approach for both infrastructure and applications. This approach includes deployable solutions for migrating these common workloads to Azure.

There are also clear recommendations in the Azure Landing Zone documentation that cover best practices for platform implementation. Therefore, we should also take the into consideration as we build out some key recommendations.

need to add ! ESLZ link to design areas??
  
## Consider the tools to build your monitoring solution

Your organization should plan to build standardized solutions using a combination of tools such as:

Azure Resource Manager templates.
Azure Policy monitoring initiative definitions and policies.
GitHub to establish a source control for the scripts, code, and documentation.

In addition, there are some key components that will figure in your monitoring suite:

Azure Monitor including Log Analytics workspace and playbooks
Microsoft Defender For Cloud
Azure Service Health
Azure Resource Health
Azure Policy and Blueprints
Azure ARC
Azure Automation
Logic Apps
Event Hubs
Sentinel

## Our Recommendations to start

You should understand that your monitoring strategy will evolve over time and be careful not to delay by ensuring you have every base covered.
Your first objective is to ensure "Observability." You need to capture some key information about your resources which will allow you to both monitor your environment but also learn for future evolution.

This is based on the MVP of 2 teams: adoption and governance where these teams are assigned th functions of cloud operations and cloud plaftorm.

Do we split into: 
cloud operations - Monitor performance of workloads
Cloud platform - Operate and manage the cloud platform

## Cloud Platform Monitoring
1. Who - cares/responds to alerts?
2. What - which alerts
3. How - which tools
4. Optimisation - review & improve

Create one or more Log Analytics workspaces.
1 per region as per guidelines - these will capture platform logs. For non-paas (solutions platforms??) create additional?
START HERE

Enable agents.

Enable resource diagnostic settings.

Enable initial alert rules.



## Cloud Operations Monitoring
1. Who - cares/responds to alerts?
2. What - which alerts
3. How - which tools
4. Optimisation - review & improve






Azure Monitor workbooks on github - https://github.com/microsoft/AzureMonitorCommunity/tree/master/Scenarios

## Next Steps

TBD 

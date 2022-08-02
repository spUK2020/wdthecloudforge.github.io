---
title: Azure DevOps setup and operating model
description: Prescriptive Azure DevOps setup and operating model
author: William Darnell
ms.author: wdthecloudforge
ms.date: 06/20/2022
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: general
ms.custom: internal, operating-model
---

# Azure DevOps Setup and Operating Model

Azure DevOps has a number of different services that need to be considered when setting up the service and the operational model to support the use and adoption by teams. It's key to look at the structure of an orgnaisation to best align this model for supporting growth and usability movings forward. 

This guide is perscriptive in providing a way to get started with a view to scale moving forward.

## Get Started

Azure DevOps consists of a number of diffferent structures and products that need to be considered where setting up the service. This will be covered in the sections below.

tbc show diagram with products

## Organisation

### What is an organisation?

It's the primary entity point into Azire DevOps where projects and supporting products are hosted. 

One Organisation -> Multiple Projects -> multiple repos (tbc  create diagram)

### One or Multiple Organisations

One organisation works for most scenarios and is a good starting point where multiple projects and teams can be added to an orgnaisation, which can drive productivity and adoption initially.  

Going with a multiple organisations model is generally driven by the need for teams and projects to work in isolation and/or require a different security model across different of a company.

## Teams

tbc - roles

## Projects

An organsaition can have multiple projects and it's key to look at the project structure. Asking questions like 
- Do we need one project per Team?
- Do we need one project per Business Area?
- Do we need one project per product?
- How do we collabvorate across teams and projects?
- How much organisational structure change do we expect?

The questions above start to build out a picture that informs the Azure DevOps project and also can impact the organisation design.

As if there's a lot of organisational sturcture change. How would you make sure the Azure DevOps design can handle it without a lot of redesign and moving projects and teams around? 

Some examples:

- By creating a project per Business Process Area (e.g. Payments) if the names and structure of the organisation changes the Payments BPA project should still be valid including the team membership.
...


## Repositories



## Boards

## Pipelines

## Additional

### Area Paths

### Tagging

## Next steps

TBD

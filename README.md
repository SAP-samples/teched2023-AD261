[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2023-AD261)](https://api.reuse.software/info/github.com/SAP-samples/teched2023-AD261)

# Session ID - AD261

## Description

This repository contains the material for the SAP TechEd 2022 session called Session ID - Manage the Propagation of Content Types Based on SAP BTP with SAP Cloud ALM.  

## Overview

Teched Hands-On Guide for Content Management using Content Agent, Cloud Transport and Cloud ALM service.
Cloud application solutions, for example, SAP S/4HANA, SAP Cloud Integration, and SAP Workflow Management publishes content to the SAP API Business Hub. Depending on your requirement, you can import, and transport across various landscapes. Also, you can assemble different content types and export.Each service has its own content format to solve a specific business / technical problem. 

Challenges 
1.	Transparency of deployed Content
2.	Which Version of Content 
3.	See the Content Status
4.	Trigger selective Transport across Accounts
5.	Clone an account / Clone a Service subscription 
6.	See Content and Application Dependencies 

Key Capabilities and Benefits: 

1.	Simple onboarding, Service subscription and One time Setup
2.	Added Governance with Cloud ALM and standardised change process
3.	Provide separation of concerns with audit trail of changes with SAP Cloud Transport Management Service 
4.	Better productivity for developers, operators and supervisors.
5.	Transparency of content transports and control with authorizations
6.	Less manual transport errors


![Overview](exercises/ex0/images/Overview.png)

## Requirements

Tools Overview for content transports 
 - Local SAP Content Agent service - A generic tool for managing content operations for different SAP BTP service.
 - Central SAP Cloud Transport Management - Central tool to manage transports of development artifacts and application-specific content
 - Central SAP Cloud ALM - An application lifecycle management offering for cloud-centric customers. It provides capabilities for implementation and operations of SAP and non-SAP cloud solutions. 

</br>
<b>Personas</b>
</br></br>
1. As a Content Operator you have the knowledge of all solutions and content live in their organization.
You responsible to collect changes across SAP BTP applications via standard channel to ensure smooth deliveries. 
You tasks are to streamline content changes, create packages for related content and trigger the export process for these changes using Transport Management service mode.
You will be using SAP Content Agent service for exporting the content. 
</br></br>
2. As a Change Manager you are responsible to keep application changes up-to-date across all landscapes.
Your tasks include review and approve changes and to monitor transport requests propagation into target accounts
You will be using Cloud Transport Management and Cloud ALM to manage distribution of changes.

## Exercises

- [Getting Started - Prerequisites](exercises/ex0/README.md)
- [Exercise 1 - Create SAP Cloud ALM Feature](exercises/ex1/README.md)
- [Exercise 2 - Export content using Content Agent service](exercises/ex2/README.md)
- [Exercise 3 - Deploy to TEST using features](exercises/ex3/README.md)
- [Exercise 4 - Deploy to Production](exercises/ex4/README.md)
- [Exercise 5 - Confirm Production Deployment](exercises/ex5/README.md)  


## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.

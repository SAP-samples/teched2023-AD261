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

o	Simple onboarding, Service subscription and One time Setup
o	Added Governance with Cloud ALM and standardised change process
o	Provide separation of concerns with audit trail of changes with SAP Cloud Transport Management Service 
o	Better productivity for developers, operators and supervisors.
o	Transparency of content transports and control with authorizations
o	Less manual transport errors


![Overview](exercises/ex0/images/Overview.png)

## Requirements

Tools Overview for content transports 
 - SAP Content Agent service is a generic tool for managing content operations for different SAP BTP service.
 - SAP Cloud Transport Management is the tool to manage transports of development artifacts and application-specific content
 - SAP Cloud ALM is an application lifecycle management offering for cloud-centric customers. It provides capabilities for implementation and operations of SAP and non-SAP cloud solutions. 

## Exercises

- [Getting Started Prerequisites already configured](exercises/ex0/)
- [Exercise 1 - Create SAP Cloud ALM Feature](exercises/ex1/)
- [Exercise 2 - Export content using Content Agent service](exercises/ex2/)
- [Exercise 3 - Deploy to TEST using features in Cloud ALM](exercises/ex3/)
- [Exercise 4 - Deploy to Production using Cloud Transport Management](exercises/ex4/)
- [Exercise 4 - View deployed content in Prod account](exercises/ex5/)  

**IMPORTANT**

Your repo must contain the .reuse and LICENSES folder and the License section below. DO NOT REMOVE the section or folders/files. Also, remove all unused template assets(images, folders, etc) from the exercises folder. 

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.

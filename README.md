[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2023-AD261)](https://api.reuse.software/info/github.com/SAP-samples/teched2023-AD261)

# Session ID - AD261
SAP Teched Hands-On Guide for Content Management using SAP Content Agent service, SAP Cloud Transport Management, and SAP Cloud ALM.

## Description

This repository contains the material for the SAP TechEd 2022 session called **AD261 - Manage the Propagation of Content Types Based on SAP BTP with SAP Cloud ALM**. 

## Overview

Cloud application solutions, for example applications on SAP S/4HANA Cloud, public edition, SAP Cloud Integration, or SAP Workflow Management publish content to the SAP Business Accelerator Hub. Depending on your requirement, you can import, and transport this content across various landscapes. Also, you can assemble different content types and export them. Each service has its own content format to solve specific business or technical problems. 

### Challenges 
1.	No standardized solution for different SAP BTP services
2.	Trigger selective transport across accounts. Manual effort in export and import operations
3.	Transparency of deployed content with the status
4.	Visualize Content and Application Dependencies
5.	No Operations view of performed activity
6.	No added governance for change management policies
7.  No audit trail of past activities


### Key Capabilities and Benefits 

1.	Simple onboarding, service subscription and one-time setup
2.	Added governance with SAP Cloud ALM and standardized change processes
3.	Provide a separation of concerns with the audit trail of changes with SAP Cloud Transport Management Service 
4.	Better productivity for developers, operators, and supervisors.
5.	Transparency of content transports and control with authorizations
6.	Less manual transport errors

<img src="exercises/ex0/images/Overview.png" width="1000">

## Requirements

Tools Overview for content transports 
 - SAP Content Agent service - A generic tool for managing content operations for different SAP BTP service. This service is offered free and auto-entitled and operates at sub account level
 - SAP Cloud Transport Management - A tool to manage transports of development artifacts and application-specific content. The service is subscribed centrally per SAP BTP global account to effectively manage cloud landscape for transports.
 - SAP Cloud ALM - An application lifecycle management offering for cloud-centric customers. It provides capabilities for implementation and operations of SAP cloud solutions. This service is also subscribed centrally per SAP BTP global account.

### Goal
The goal of this exercise is to propagate content from different SAP BTP applications across a three-tier landscape consisting of DEV, TEST, and PROD subaccounts.

  As a *content operator* you have comprehensive knowledge of all solutions and content within your organization. You are responsible for collecting changes from SAP BTP applications via standard channels to ensure smooth deliveries. To accomplish this, you will use **SAP Content Agent service** to export content from the DEV subaccount and create a transport request in SAP Cloud Transport Management.
  
 
  As a *change manager*, you are responsible for keeping application changes up-to-date across all landscapes using transport routes configured in **SAP Cloud Transport Management**.
To review, approve, and monitor the propagation of changes into target accounts, you will use the **SAP Cloud ALM** Features app, leveraging its workflow capabilities to orchestrate the deployment of transport requests into the TEST and PROD environments.

## Exercises

- [Getting Started - Prerequisites](exercises/ex0/README.md)
- [Exercise 1 - Create a Feature in SAP Cloud ALM](exercises/ex1/README.md)
- [Exercise 2 - Export Content Using SAP Content Agent Service](exercises/ex2/README.md)
- [Exercise 3 - Deploy to TEST Using the Features App in SAP Cloud ALM](exercises/ex3/README.md)
- [Exercise 4 - Deploy to Production Using SAP Cloud Transport Management](exercises/ex4/README.md)
- [Exercise 5 - Confirm Production Deployment](exercises/ex5/README.md)  

## Resources

- [Help Portal Product Page](https://help.sap.com/docs/content-agent-service?locale=en-US)
- [Blog: New User Interface for Content Agent Service](https://blogs.sap.com/2022/08/09/new-user-interface-for-content-agent-service/)
- [How to use SAP Content Agent Service](https://blogs.sap.com/2022/09/05/how-to-use-sap-content-agent-service-video/)
- [Roadmap](https://roadmaps.sap.com/board?range=CURRENT-LAST&PRODUCT=73555000100800002111#Q4%202023)


## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.

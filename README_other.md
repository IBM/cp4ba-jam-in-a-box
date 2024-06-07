# Jam-in-a-Box for Business Automation - Other Environments

## Quick Start

1. Select the **solution** and **version** of the asset of interest from the [Solutions and Assets](#solutions-and-assets) section
2. Follow the instructions in the **Quick Start** section of the linked document

## Introduction

The [Solutions and Assets](#solutions-and-assets) section below lists the available assets that can be imported into an **existing** Cloud Pak for Business Automation (CP4BA) environment.

In case you don't have an existing CP4BA environment, please follow these [instruction](README.md) on how to request an environment that is pre-deployed and pre-configured with the Client Onboarding solution.

## Solutions and Assets

### Client Onboarding

The [Client Onboarding](https://github.com/IBM/cp4ba-client-onboarding-scenario) scenario is an end-to-end demo for Cloud Pak for Business Automation that covers the following components: Automation Decision Services, Automation Document Processing, Workflow, Content, Robotic Process Automation, Business Automation Insights.

More information on the assets, how to reserve an environment and the labs are listed below for the versions of CP4BA that are currently supported (versions not mentioned are not or no longer supported!)

- [CP4BA 23.0.2](https://github.com/IBM/cp4ba-jam-in-a-box/tree/main/Solutions/Client%20Onboarding/README.md)
- [CP4BA 23.0.1](https://github.com/IBM/cp4ba-jam-in-a-box/tree/main/Solutions/Client%20Onboarding/README_2301.md) - Deprecated

### Email Server and Web-based Email Client

It can be useful to have an email server and client locally deployed within a Cloud Pak for Business Automation instance. While this email server can only handle emails locally, other CP4BA capabilities can be connected to it, e.g. to send notifications. In that way the CP4BA instance is self-contained without external dependencies.

Follow these [instructions](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/DeployingEmailServerClient.md) to deploy such a setup into a CP4BA 22.0.2, 23.0.1, or 23.0.2 Starter deployment environment. It will also also you to add additional users to the CP4BA environment which can be useful for demos.


## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners and IBMers**

To engage us, drop us a message at [#jam-in-a-box-business-automation](https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T).

**All others**

Open a new issue in this GitHub

## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

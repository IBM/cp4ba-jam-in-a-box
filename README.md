# Jam-in-a-Box for Business Automation

#### Cloud Pak for Business Automation Version: 22.0.2

## Introduction

The Jam-in-a-Box environments provides the ability to demo out-of-box solutions, run your own mini-Tech Jam, or get self-educated on Business Automation.

Jam-in-a-Box removes hurdles to Business Automation adoption through easing availability and sharing of technical enablement. Towards this it offers a set of self-provisionable environments hosted on IBM TechZone, combined with a set of hands-on technical labs spanning all capabilities of Business Automation.

## Use cases for Jam-in-a-Box

### 1. Technical Enablement

1. Self-enablement - use the environment to gain hands-on experience on one or all capabilities of Business Automation using a realistic business scenario
2. Client-enablement - use the environment to host a mini-Tech-Jam for your clients

### 2. Demo/PoX

1. Demo - use the out-of-box solutions to present a live demo of Business Automation capabilities
2. PoX - use the environments as a base to customize/extend the business scenario based on your client’s needs

## Software Used

- Infrastructure from TechZone (different labs use different environments, for details see below)
   - Managed Red Hat OpenShift (OCP 4.10) on IBM Cloud
   - IBM Cloud Pak for Business Automation 22.0.2 IF002
   - IBM Process Mining 1.13.2
   - IBM Robotic Process Automation 23.0.2

## Available Solutions and Assets

### 1. Client Onboarding

**Introduction:** The [Client Onboarding](https://github.com/IBM/cp4ba-client-onboarding-scenario) scenario is an end-to-end demo for Cloud Pak for Business Automation that covers the following components: Automation Decision Services, Automation Document Processing, Workflow, Content, Robotic Process Automation, Business Automation Insights

**Assets:** The solution has [nine hands-on labs](https://github.com/IBM/cp4ba-labs/tree/main/22.0.2) associated with it.

**Jax-in-a-box-enviornment:** In order to deploy the solution in your own Jam-in-a-box environment, deploy the Client Onboarding solution as described in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/DeployingClientOnboarding2202.md). The document also contains hints in case you don't have access to/can't aget an IBM TechZone environment.

**Mapping of labs to environments**

Most labs are accessible using the Jam-in-a-box environment. For some labs, you will need a separate environment as described below:

| Lab(s)                                                       | Environment (IBM TechZone - Business Partners and IBMers only) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [IBM Cloud Pak for Business Automation (End-to-End)](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/IBM%20Cloud%20Pak%20for%20Business%20Automation%20(End-to-End))<br/>[IBM Business Automation Application](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Business%20Automation%20Application)<br/>[IBM Business Automation Insights](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Business%20Automation%20Insights)<br/>[IBM FileNet Content Services](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Content)<br/>[IBM Automation Decision Services](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Decisions)<br/>[IBM Business Automation Workflow](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Workflow) | Jam-in-a-box environment (deployment instructions are availabe in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/DeployingClientOnboarding2202.md)) |
| [IBM CP4BA - Bring-up Lab](https://github.com/IBM/cp4ba-labs/blob/main/22.0.1/Bring-up) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/22.0.1/Bring-up) (CP4BA 22.0.1) |
| [IBM Process Mining](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Process%20Mining) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/22.0.2/Process%20Mining) |
| [IBM Robotic Process Automation](https://github.com/IBM/cp4ba-labs/blob/main/22.0.1/Robotic%20Process%20Automation) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/22.0.1/Robotic%20Process%20Automation) |


## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners and IBMers**
To engage us, drop us a message at [#jam-in-a-box-business-automation](https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T).


**All others**
Open a new issue in this GitHub

## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

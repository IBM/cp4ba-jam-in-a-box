# Jam-in-a-Box for Business Automation & Digital Labor

## Quick Start

1. Select the lab(s) you are interested in in the left column of the table of the [Labs to Environments Mapping](#labs-to-environments-mapping) section
2. Follow the instructions in the right column of the table to request the appropriate environment



## Introduction

The [Client Onboarding](https://github.com/IBM/cp4ba-client-onboarding-scenario) scenario is an end-to-end demo for Cloud Pak for Business Automation (CP4BA) and selected aspects of watsonX Orchestrate (wxO). 

The CP4BA part covers the following components: Automation Decision Services (ADS), Automation Document Processing (ADP), Business Automation Applications (BAA), Workflow, Content, Robotic Process Automation (RPA), Business Automation Insights (BAI). The wxO part covers skill, skill flow, and automation building.

Labs for each capability provide an easy way to gain familiarity with the development aspects to build the respective parts of the Client Onboarding solution.

The Jam-in-a-Box environments provide the ability to demo the out-of-box end-to-end [Client Onboarding](https://github.com/IBM/cp4ba-client-onboarding-scenario) solution and more, run your own mini-Tech Jam, or get self-educated on Business Automation and watsonX Orchestrate as part of Digital Labor.

Jam-in-a-Box removes hurdles to Business Automation and Digital Labor adoption through easing availability and sharing of technical enablement. Towards this it offers a set of self-provisionable environments hosted on IBM TechZone, combined with a set of hands-on technical labs spanning all capabilities of Business Automation and watsonX Orchestrate (for watsonX Orchestrate a separate wxO SaaS instance is required).



## Use Cases for Jam-in-a-Box

### 1. Technical Enablement

1. Self-enablement - use the environments to gain hands-on experience on one or all capabilities of Business Automation and Digital Labor using a realistic business scenario
2. Client-enablement - use the environments to host a mini-Tech Jam for your clients

### 2. Demo/PoX

1. Demo - use the out-of-box Client Onboarding solution and more to present a live demo of Business Automation and Digital Labor capabilities
2. PoX - use the environments as a base to customize/extend the business scenario based on your client’s needs



## Labs to Environments Mapping

Most labs are accessible using a single Jam-in-a-Box environment. For some labs, you will need a separate environment. The table below provides the respective details:

| Lab(s)                                                       | Environment (IBM TechZone - Business Partners and IBMers only) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [IBM Cloud Pak for Business Automation (End-to-End)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/IBM%20Cloud%20Pak%20for%20Business%20Automation%20(End-to-End)) <br/>-<br/>[IBM Business Automation Application](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Application) <br/>-<br/>[IBM Automation Decision Services](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Decisions) <br/>-<br/>[IBM Automation Document Processing](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Document%20Processing)<br/>-<br/>[IBM Business Automation Insights](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Insights)<br/>-<br/>[IBM Business Automation Workflow](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Workflow)<br/>-<br/>[IBM FileNet Content Services (CPE, GraphQL & Navigator)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Content) | See section [Environment Selection for Core Labs](#environment-selection-for-core-labs) below |
| [IBM watsonx Orchestrate](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/watsonx%20Orchestrate) | Pre-deployed Client Onboarding from TechZone based on [Apollo Business Automation CP4BA Demo](/Solutions/Client%20Onboarding/README_2302_ApolloBA_CP4BADemos.md)<br/><br/> **Remarks:**<br/>- Access to a watsonx Orchestrate SaaS instance is required as an additional prerequisite. Please check the watsonx Orchestrate content on Seismic to learn how to get access to such an instance.<br/>- The Jam-in-a-Box environment above can currently only be accessed from the bastion host of the environment. Therefore, it does not support the watsonX Orchestrate lab yet. |
| [IBM Process Mining](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Process%20Mining) | One environment required per user in case of mini-Tech Jams!<br/>Please reserve a TechZone Process Mining Environment [here](https://techzone.ibm.com/collection/process-mining-with-task-mining-demo-and-etl/environments). Make sure to select the **IBM Process Mining 1.14.3 with Task Mining and ETL - US East only**. |
| [IBM Robotic Process Automation](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Robotic%20Process%20Automation) | One environment required per user in case of mini-Tech Jams!<br/>Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/Robotic%20Process%20Automation) |
| [IBM CP4BA - Bring-up (Deployment of CP4BA)](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/Bring-up) | One environment required per user in case of mini-Tech Jams!<br/>Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/Bring-up) |

> [!NOTE]
>
> The options mentioned for the first two rows are focused on TechZone environments with **pre-deployed** Client Onboarding assets. If you have your own CP4BA environment (from TechZone or not), into which you want to deploy the Client Onboarding assets yourself, please refer to this [document](README_other.md) for details.



## Environment Selection for Core Labs

- **Single-user/self-paced** Client Onboarding demo and labs on **CP4BA 23.0.2**
  - [Pre-deployed Client Onboarding from TechZone](/Solutions/Client%20Onboarding/README.md)
    - **Benefits:** Provisioning time only 2-3 hours; Support of ADP lab
    - **Limitations:** Need to use RDP to connect to bastion host to perform demo/labs; No support for RPA as part of Client Onboarding demo; No support for watsonX Orchestrate lab (all three to be lifted)
  - [Pre-deployed Client Onboarding from TechZone based on Apollo Business Automation CP4BA Demos](/Solutions/Client%20Onboarding/README_2302_ApolloBA_CP4BADemos.md)
    - **Benefits:** Accessible from any web browser; Supports watsonX Orchestrate lab; Supports ADP lab
    - **Limitations:** Provisioning time 5-7 hours; No support for RPA as part of Client Onboarding demo
- **Workshop/Mini-Tech Jam** with 10-20 participants on **CP4BA 23.0.2**
  - Pre-deployed Client Onboarding from TechZone (coming soon)
    - **Benefits:** Provisioning time only 2-3 hours; Comes with 20 users for mini-Tech Jams; Accessible from any web browser; Supports watsonX Orchestrate lab; Can be configured to use RPA as part of Client Onboarding demo
    - **Limitations:** No support for ADP lab (due to ADP design limitations)
  - [Pre-deployed Client Onboarding from TechZone based on Apollo Business Automation CP4BA Demos](/Solutions/Client%20Onboarding/README_2302_ApolloBA_CP4BADemos.md)
    - **Benefits:** Comes with 20 users for mini-Tech Jams; Accessible from any web browser; Supports watsonX Orchestrate lab
    - **Limitations:** Provisioning time 5-7 hours; No support for RPA as part of Client Onboarding demo; No support for ADP lab as part of mini-Tech Jam (due to ADP design limitations)



## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners and IBMers**

To engage us, drop us a message at [#jam-in-a-box-ba-dl](https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T).

**All others**

Open a new issue in this GitHub



## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

# Jam-in-a-Box for Business Automation (CP4BA 23.0.2)

## Quick Start

1. Select the lab you are interested in on the left column of the table of the [Labs to Environments Mapping](#labs-to-environments-mapping) section
2. Follow the instructions in the right column of the table to request the appropriate environment



## Introduction

The <a href="https://github.com/IBM/cp4ba-client-onboarding-scenario" target="_blank">Client Onboarding</a> scenario is an end-to-end demo for Cloud Pak for Business Automation (CP4BA). 

The CP4BA part covers the following components: Automation Decision Services (ADS), Automation Document Processing (ADP), Business Automation Applications (BAA), Workflow, Content, Robotic Process Automation (RPA), Business Automation Insights (BAI).

Labs for each capability provide an easy way to gain familiarity with the development aspects to build the respective parts of the Client Onboarding solution.

The Jam-in-a-Box environments provide the ability to demo the out-of-box end-to-end <a href="https://github.com/IBM/cp4ba-client-onboarding-scenario" target="_blank">Client Onboarding</a> solution and more, run your own mini-Tech Jam, or get self-educated on Business Automation.

Jam-in-a-Box removes hurdles to Business Automation adoption through easing availability and sharing of technical enablement. Towards this it offers a set of self-provisionable environments hosted on IBM TechZone, combined with a set of hands-on technical labs spanning all capabilities of Business Automation.



## Use Cases for Jam-in-a-Box

### 1. Technical Enablement

1. Self-enablement - use the environments to gain hands-on experience on one or all capabilities of Business Automation using a realistic business scenario
2. Client-enablement - use the environments to host a mini-Tech Jam for your clients

### 2. Demo/PoX

1. Demo - use the out-of-box Client Onboarding solution and more to present a live demo of Business Automation capabilities
2. PoX - use the environments as a base to customize/extend the business scenario based on your client’s needs



## Labs to Environments Mapping

Most labs are accessible using a single Jam-in-a-Box environment. For some labs, you will need a separate environment. The table below provides the respective details:

| Lab(s)                                                       | Environment (IBM TechZone - Business Partners and IBMers only) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [IBM Cloud Pak for Business Automation (End-to-End)](23.0.2/IBM Cloud Pak for Business Automation (End-to-End)\README.md) <br/>-<br/>[IBM Business Automation Application](23.0.2/Business Automation Application\README.md) <br/>-<br/>[IBM Automation Decision Services](23.0.2/Decisions\README.md) <br/>-<br/>[IBM Automation Document Processing](23.0.2/Document Processing\README.md)<br/>-<br/>[IBM Business Automation Insights](23.0.2/Business Automation Insights\README.md)<br/>-<br/>[IBM Business Automation Workflow](23.0.2/Workflow\README.md)<br/>-<br/>[IBM FileNet Content Services (CPE, GraphQL & Navigator)](23.0.2/Content\README.md) | See section [Environment Selection for Core Labs](#environment-selection-for-core-labs) below |
| [IBM Process Mining](23.0.2/Process Mining\README.md)        | One environment required per user in case of mini-Tech Jams!<br/>Please reserve a TechZone Process Mining Environment <a href="https://techzone.ibm.com/collection/process-mining-with-task-mining-demo-and-etl/environments" target="_blank">here</a>. Make sure to select the **IBM Process Mining 1.15 with Task Mining and ETL - Multizone**. |
| [IBM Robotic Process Automation](23.0.2/Robotic Process Automation\README.md) | One environment required per user in case of mini-Tech Jams!<br/>Follow the instructions provided on the respective [lab overview page](23.0.2/Robotic Process Automation\README.md) |
| [IBM CP4BA - Bring-up (Deployment of CP4BA)](23.0.2/Bring-up\README.md) | One environment required per user in case of mini-Tech Jams!<br/>Follow the instructions provided on the respective [lab overview page](23.0.2/Bring-up\README.md) |

!!! Note
>
> The options mentioned for the first two rows are focused on TechZone environments with **pre-deployed** Client Onboarding assets. If you have your own CP4BA environment (from TechZone or not), into which you want to deploy the Client Onboarding assets yourself, please refer to this [document](23.0.2/Solutions/Client%20Onboarding/README_2302_SelfDeploy.md) for details.



## Environment Selection for Core Labs

- **Single-user/self-paced** Client Onboarding demo and labs on **CP4BA 23.0.2**
    - [Pre-deployed Client Onboarding from TechZone](23.0.2/Solutions/Client%20Onboarding/README.md)
        - **Benefits:** Provisioning time only 2-3 hours; Supports ADP lab
        - **Limitations:** Need to use Remote Desktop client (RDP) to connect to bastion host to perform demo/labs; No support for watsonx Orchestrate lab
    - Pre-deployed Client Onboarding from TechZone based on Apollo Business Automation CP4BA Demos
        - No longer available, refer to [CP4BA 25.0.0](25.0.0/README.md)
    
- **Workshop/Mini-Tech Jam** with 10-20 participants on **CP4BA 23.0.2**
    - No longer available, refer to [CP4BA 25.0.0](25.0.0/README.md)



## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners and IBMers**

To engage us, drop us a message at <a href='https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T' target = '_blank'>#jam-in-a-box-ba-dl</a>.

**All others**

For anyone who doesn’t fall into the business partner or IBM employee category, please feel free to open a new issue on our <a href="https://github.com/IBM/cp4ba-jam-in-a-box/issues" target="_blank">GitHub repository</a>. We’ll be more than happy to address your questions and concerns there.



## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.


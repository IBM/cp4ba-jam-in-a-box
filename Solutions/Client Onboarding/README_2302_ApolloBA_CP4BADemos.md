# CP4BA Demos Environment based on Apollo Business Automation/Cloud Pak Deployer for CP4BA 23.0.2

> [!IMPORTANT]
>
> - As this approach relies on reserving an environment from IBM TechZone, this document is **only applicable to IBM Business Partners** that have the ability to request environments from TechZone **and IBMers**. 
> - The **RPA** part of the Client Onboarding scenario is not configured.
> 
>If you have your own Cloud Pak for Business Automation (CP4BA) 23.0.2 environment or need the RPA bot in action, please refer to this [document](../../README.md) for other options.



## Quick Start

1. Reserve a CP4BA Demos environment as described in the [section](#reserve-the-cp4ba-demos-environment) below
1. Read the [Lab Considerations](#lab-considerations) section for specifics of using the labs in the context of this CP4BA Demos environment
1. Follow the link to the documentation of the lab you want to perform in the [Lab Instructions](#lab-instructions) section



## **Overview**

This Jam-in-a-Box environment is provided to you as a cooperation between the owners of the Apollo Business Automation approach and the IBM Business Automation and Digital Labor SWAT team.

The major benefits of using this environment are:

- This environment can be used for a single user use case or for running mini-Tech Jams with at least 10 participants
- Client Onboarding scenario and lab artifacts are pre-deployed for you
- 20 business users have been that can be given to participants of a mini-Tech Jam

> [!CAUTION]
>
> It can take 5-7 hours until the environment is available.



## Reserve the CP4BA Demos Environment

Follow the journey [Apollo Business Automation - CP4BA Demos](https://techzone.ibm.com/collection/apollo-business-automation/journey-cp4ba-demos) to reserve your environment on IBM TechZone. It consists of three major steps:

1. Requesting the environment in step 1 and waiting till the environment is **Ready** and fully deployed. This will normally take approximately 5-7 hours.
2. Validating the successful deployment of the Cloud Pak for Business Automation as described in step 2.
3. Validating the successful deployment of the Client Onboarding scenario as described in step 3.



## Labs Instructions & Considerations

#### Lab Considerations

The lab instructions are written in context of a Tech Jam event. When performing the labs as part of Jam-in-a-Box keep in mind:

| Lab instructions mention...                                  | As part of this Jam-in-a-Box environment...                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| using the **URLs** found on the Tech Jam event page          | please login to the OpenShift console, go to **Workloads -> ConfigMaps** and search for **client-onboarding-information**.<br />The ConfigMap contains all relevant URLs for this environment. |
| how to receive your **user credentials** using a link on the Tech Jam event page | please login to the OpenShift console, go to **Workloads -> ConfigMaps** and search for **client-onboarding-information**.<br />The ConfigMap contains all relevant user names and password for this environment. |
| to **prefix your artifacts** with "usrXYZ"                   | depending on if you use the environment as a single-user environment or for running a mini-Tech Jam, you may choose to follow the instructions in this point |



#### Lab Instructions

Below you find the links to the lab instructions for the labs supported in this environment:

- [IBM Cloud Pak for Business Automation (End-to-End)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/IBM%20Cloud%20Pak%20for%20Business%20Automation%20(End-to-End))
- [IBM Business Automation Application](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Application)
- [IBM Automation Decision Services](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Decisions)
- [IBM Automation Document Processing](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Document%20Processing) (only for single-user usage)
- [IBM Business Automation Insights](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Insights)
- [IBM Business Automation Workflow](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Workflow)
- [IBM FileNet Content Services (CPE, GraphQL & Navigator)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Content)
- [IBM watsonx Orchestrate](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/watsonx%20Orchestrate) (requires a separate watsonX Orchestrate SaaS tenant)



## Support

We aim to support successfully utilizing our assets as part of Jam-in-a-Box. For questions and issues around Apollo Business Automation, please reach out to its [authors](https://techzone.ibm.com/collection/apollo-business-automation). 

For questions and issues around the Client Onboarding labs:

**Business Partners (require an invitation) and IBMers**

To engage us, drop us a message at [#jam-in-a-box-business-automation](https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T).

**All others**

Open a new issue in this GitHub



## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

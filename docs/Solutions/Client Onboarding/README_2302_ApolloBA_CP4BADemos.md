# CP4BA Demos Environment based on Apollo Business Automation/Cloud Pak Deployer for CP4BA 23.0.2

> [!IMPORTANT]
>
> - As this approach relies on reserving an environment from IBM TechZone, this document is **only applicable to IBM Business Partners** that have the ability to request environments from TechZone **and IBMers**. 
> - The **RPA** part of the Client Onboarding scenario is not configured.
> 
>If you have your own Cloud Pak for Business Automation (CP4BA) 23.0.2 environment or need the RPA bot in action, please refer to this [document](../../index.md) for other options.



## Quick Start

1. Reserve a CP4BA Demos environment as described in the [section](#reserve-the-cp4ba-demos-environment) below
1. Read the [Lab Considerations](#lab-considerations) section for specifics of using the labs in the context of this CP4BA Demos environment
1. Follow the link to the documentation of the lab you want to perform in the [Lab Instructions](#lab-instructions) section



## **Overview**

This Jam-in-a-Box environment is provided to you as a cooperation between the owners of the Apollo Business Automation approach and the IBM Business Automation and Digital Labor SWAT team.

The major benefits of using this environment are:

- Environment can be used for a single-user use case and for running mini-Tech Jams with approximately 10 participants (feedback welcome if you used it more users)
- Client Onboarding scenario and lab artifacts are pre-deployed for you
- 20 business users have been created that can be given to participants of a mini-Tech Jam

> [!CAUTION]
>
> It can take 5-7 hours until the environment is available.



## Reserve the CP4BA Demos Environment

Follow the journey [Apollo Business Automation - CP4BA Demos](https://techzone.ibm.com/collection/apollo-business-automation/journey-cp4ba-demos) to reserve your environment on IBM TechZone. It consists of three major steps:

1. Requesting the environment in step 1 and waiting till the environment is **Ready** **and fully deployed**. This will normally take approximately 5-7 hours.
2. Validating the successful deployment of the Cloud Pak for Business Automation as described in step 2.
3. Validating the successful deployment of the Client Onboarding scenario assets as described in step 3.



## Labs Instructions & Considerations

#### Lab Considerations

The lab instructions are written in context of a Tech Jam event. When performing the labs as part of Jam-in-a-Box keep in mind:

| Lab instructions mention...                                  | As part of this Jam-in-a-Box environment...                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| using the **URLs** found on the Tech Jam event page          | please login to the OpenShift console, go to **Workloads -> ConfigMaps** and search for **client-onboarding-information**.<br />The ConfigMap contains all relevant URLs for this environment. <br />For a mini-Tech Jam share them with the participants in a suitable form. |
| how to receive your **user credentials** using a link on the Tech Jam event page | please login to the OpenShift console, go to **Workloads -> ConfigMaps** and search for **client-onboarding-information**.<br />The ConfigMap contains all relevant user names and password for this environment.<br />For a mini-Tech Jam share a dedicated user name and password with each participants in a suitable form. |
| to **prefix your artifacts** with "usrXYZ"                   | depending on if you use the environment as a single-user environment or for running a mini-Tech Jam, you may choose to follow the instructions in this point |



#### Lab Instructions

Below you find the links to the lab instructions for the labs supported in this environment:

- [IBM Cloud Pak for Business Automation (End-to-End)](../../IBM Cloud Pak for Business Automation (End-to-End)\README.md)
- [IBM Business Automation Application](../../Business Automation Application\README.md)
- [IBM Automation Decision Services](../../Decisions\README.md)
- [IBM Automation Document Processing](../../Document Processing\README.md) (only for single-user usage)
- [IBM Business Automation Insights](../../Business Automation Insights\README.md)
- [IBM Business Automation Workflow](../../Workflow\README.md)
- [IBM FileNet Content Services (CPE, GraphQL & Navigator)](../../Content\README.md)
- [IBM watsonx Orchestrate](../../watsonx Orchestrate\README.md) (requires a separate watsonX Orchestrate SaaS tenant)



## Support

We aim to support successfully utilizing our assets as part of Jam-in-a-Box. For questions and issues around Apollo Business Automation, please reach out to its [authors](https://techzone.ibm.com/collection/apollo-business-automation). 

For questions and issues around the Client Onboarding labs:

**Business Partners (require an invitation) and IBMers**

To engage us, drop us a message at <a href="https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T" target="_blank">#jam-in-a-box-ba-dl</a>.

**All others**

For anyone who doesn’t fall into the business partner or IBM employee category, please feel free to open a new issue on our <a href="https://github.com/IBM/cp4ba-jam-in-a-box/issues" target="_blank">GitHub repository</a>. We’ll be more than happy to address your questions and concerns there.



## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

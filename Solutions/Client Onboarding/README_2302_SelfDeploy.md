# Jam-in-a-Box - Client Onboarding for CP4BA 23.0.2/watsonX Orchestrate - Deploying the Assets Yourself

## Quick Start

1. Read the [Lab Considerations](#lab-considerations) section for specifics of using the labs in the context of Jam-in-a-Box
1. Select the lab(s) you want to do from the table in the [**Mapping of labs to environments**](#**mapping-of-labs-to-environments**) section below
1. Follow the instructions for the lab(s) in the **right column** to get and prepare the required environment(s)
1. Follow the link(s) to the documentation of the lab(s) in the **left column** and perform the lab(s)

## **Overview**

This type of Jam-in-a-Box approach provides you with the largest flexibility to deploy the Client Onboarding assets to the environment of your choice. It is provided to you by the IBM Business Automation and Digital Labor SWAT team through the deployment tool.

The major benefits of using this environment are:

- Independent of CP4BA environment provisioned by TechZone, but supporting TechZone provisioned environments
- Full flexibility in which pieces of the Client Onboarding scenario and labs to be deployed and with which options



**Introduction to the Client Onboarding solution and solution exports:** https://github.com/IBM/cp4ba-client-onboarding-scenario 

**Jam-in-a-Box environment:** In order to use the solution in your own Jam-in-a-Box environment, deploy the Client Onboarding solution and labs as described in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/StarterDeploymentViaJob.md) for a **Starter** deployment or refer to this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/README.md) for **Enterprise** deployments.

## Labs

#### Lab Considerations

The lab instructions are written in context of a Tech Jam event. When performing the labs as part of Jam-in-a-Box keep in mind:

| Lab instructions mention...                                  | As part of this Jam-in-a-Box environment...                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| using the **URLs** found on the Tech Jam event page          | please use those URLs provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful |
| how to receive your **user credentials** using a link on the Tech Jam event page | please use the admin user and admin password (or one of the business users) provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful |
| to **prefix your artifacts** with "usrXYZ"                   | this is important when working in a shared environment. You may choose to still follow the instructions in this point, even when this is not strictly required for the Jam-in-a-Box environment (at least if a Starter pattern environment) that is normally considered a single-user environment. For the watsonx Orchestrate lab you should still do this as you are probably working on a shared watsonx Orchestrate instance with other users. |




#### **Mapping of labs to environments**

| Lab(s)                                                       | Environment (IBM TechZone - Business Partners and IBMers only) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [IBM Cloud Pak for Business Automation (End-to-End)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/IBM%20Cloud%20Pak%20for%20Business%20Automation%20(End-to-End))<br/>[IBM Automation Decision Services](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Decisions)<br/>[IBM Automation Document Processing](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Document%20Processing)<br/>[IBM Business Automation Application](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Application)<br/>[IBM Business Automation Insights](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Insights)<br/>[IBM Business Automation Workflow](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Workflow)<br/>[IBM FileNet Content Services (CPE, GraphQL & Navigator)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Content) | Jam-in-a-Box environment (deployment instructions are available in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/StarterDeploymentViaJob.md) for Starter pattern, or this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/README.md) for Enterprise pattern) |
| [IBM watsonx Orchestrate](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/watsonx%20Orchestrate) | Jam-in-a-Box environment (deployment instructions are available in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/StarterDeploymentViaJob.md) for Starter pattern, or this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/README.md) for Enterprise pattern)<br/>Access to a watsonx Orchestrate instance is required as an additional prerequisite. Please check the watsonx Orchestrate content on Seismic to learn how to get access to such an instance. |



## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners (require an invitation) and IBMers**

To engage us, drop us a message at [#jam-in-a-box-ba-dl](https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T).

**All others**

Open a new issue in this GitHub



## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

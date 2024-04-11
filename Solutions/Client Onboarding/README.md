> [!WARNING]
>
> Under construction

# Jam-in-a-Box - Client Onboarding for CP4BA 23.0.2/watsonX Orchestrate

## Quick Start

1. Select the lab(s) you want to do from the table in the [Labs](#labs) section below
1. Follow the instructions for the lab(s) in **right column** to get and prepare the required environment(s)
1. Read the [Lab Considerations](#lab-considerations) section for specifics of using the labs in the context of Jam-in-a-Box
1. Follow the link(s) to the documentation of the lab(s) in the **left column** and perform the lab(s)

## **Overview**

**Introduction of the Client Onboarding solution and solution exports:** https://github.com/IBM/cp4ba-client-onboarding-scenario 

**Lab assets:** The solution has [eleven hands-on labs](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2) associated with it

**Jam-in-a-Box environment:** In order to use the solution in your own Jam-in-a-Box environment, deploy the Client Onboarding solution and labs as described in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/StarterDeploymentViaJob.md) for a **Starter** deployment or refer to this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/README.md) for **Enterprise** deployments.

**What's included:**

- Red Hat OpenShift (OCP 4.14) on VMWare on IBM Cloud
- IBM Cloud Pak for Business Automation 23.0.2 IF002
- IBM Process Mining 1.14.3
- IBM Robotic Process Automation 23.0.13

## Labs

Most labs are accessible using the Jam-in-a-Box environment. For some labs, you will need a separate environment. The table below provides the respective details:

**Mapping of labs to environments**

| Lab(s)                                                       | Environment (IBM TechZone - Business Partners and IBMers only) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [IBM Cloud Pak for Business Automation (End-to-End)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/IBM%20Cloud%20Pak%20for%20Business%20Automation%20(End-to-End))<br/>[IBM Business Automation Application](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Application)<br/>[IBM Business Automation Insights](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Business%20Automation%20Insights)<br/>[IBM FileNet Content Services (CPE, GraphQL & Navigator)](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Content)<br/>[IBM Automation Decision Services](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Decisions)<br/>[IBM Business Automation Workflow](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Workflow)<br />[IBM Automation Document Processing](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Document Processing) | Jam-in-a-Box environment (deployment instructions are available in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/StarterDeploymentViaJob.md) for Starter pattern, or this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/README.md) for Enterprise pattern) |
| [IBM watsonx Orchestrate](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/watsonx%20Orchestrate) | Jam-in-a-Box environment (deployment instructions are available in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/StarterDeploymentViaJob.md) for Starter pattern, or this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/23.0.2/README.md) for Enterprise pattern)<br/>Access to a watsonx Orchestrate instance is required as an additional prerequisite. Please check the watsonx Orchestrate content on Seismic to learn how to get access to such an instance. |
| [IBM Process Mining](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Process%20Mining) | Please reserve a TechZone Process Mining Environment [here](https://techzone.ibm.com/collection/process-mining-with-task-mining-demo-and-etl/environments). Make sure to select the **IBM Process Mining 1.14.3 with Task Mining and ETL - US East only**. |
| [IBM Robotic Process Automation](https://github.com/IBM/cp4ba-labs/blob/main/23.0.2/Robotic%20Process%20Automation) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/Robotic%20Process%20Automation) |
| [Bring-up Lab (Deployment of CP4BA)](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/Bring-up) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/23.0.2/Bring-up) |

##### Lab Considerations

- The lab instructions refer to using the URLs found on the Tech Jam event page. For Jam-in-a-Box environments, please use those URLs provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful.
- The lab instructions mention how to receive your user credentials using a link on the Tech Jam event page. For Jam-in-a-Box environments, please use the admin user and admin password (or one of the business users) provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful. In case your Jam-in-a-Box environment uses an external LDAP check with the party that owns the LDAP on available users and passwords.
- The lab instructions mostly mention to prefix your artifacts with "usrXYZ". This is important when working in a shared environment. You may choose to still follow the instructions in this point, even when this is not strictly required for the Jam-in-a-Box environment (at least if a Starter pattern environment) that is normally considered a single-user environment. For the watsonx Orchestrate lab you should still do this as you are probably working on a shared watsonx Orchestrate instance with other users. 

## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners (require an invitation) and IBMers**

To engage us, drop us a message at [#jam-in-a-box-business-automation](https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T).

**All others**

Open a new issue in this GitHub

## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

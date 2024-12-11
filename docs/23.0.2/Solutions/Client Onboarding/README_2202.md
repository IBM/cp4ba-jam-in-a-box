# Jam-in-a-Box - Client Onboarding for CP4BA 22.0.2

## Quick Start

1. Select the lab(s) you want to do from the table in the [Labs](#labs) section below
1. Follow the instructions for the lab(s) in **right column** to get and prepare the required environment(s)
1. Read the [Lab Considerations](#lab-considerations) section for specifics of using the labs in the context of Jam-in-a-Box
1. Follow the link(s) to the documentation of the lab(s) in the **left column** and perform the lab(s)

## **Overview**

**Introduction of the Client Onboarding solution and solution exports:** https://github.com/IBM/cp4ba-client-onboarding-scenario 

**Lab assets:** The solution has <a href='https://github.com/IBM/cp4ba-labs/tree/main/22.0.2' target = '_blank'>nine hands-on labs</a> associated with it

**Jam-in-a-Box environment:** In order to use the solution in your own Jam-in-a-Box environment, deploy the Client Onboarding solution and labs as described in <a href='https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/22.0.2/DeployingClientOnboarding2202.md' target = '_blank'>this document</a>. The document also contains hints in case you don't have access to/can't get an IBM TechZone environment.

**What's included:**

- Red Hat OpenShift (OCP 4.12) on VMWare on IBM Cloud
- IBM Cloud Pak for Business Automation 22.0.2 IF005
- IBM Process Mining 1.14.1
- IBM Robotic Process Automation 23.0.2

## Labs

Most labs are accessible using the Jam-in-a-Box environment. For some labs, you will need a separate environment. The table below provides the respective details:

**Mapping of labs to environments**

| Lab(s)                                                       | Environment (IBM TechZone - Business Partners and IBMers only) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| <a href='' target = '_blank'>IBM Cloud Pak for Business Automation (End-to-End)</a> Business Automation Application](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Business%20Automation%20Application)<br/>[IBM Business Automation Insights](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Business%20Automation%20Insights)<br/>[IBM FileNet Content Services (CPE, GraphQL & Navigator)](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Content)<br/>[IBM Automation Decision Services](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Decisions)<br/>[IBM Business Automation Workflow](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Workflow) | Jam-in-a-Box environment (deployment instructions are available in this <a href='https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/22.0.2/DeployingClientOnboarding2202.md' target = '_blank'>document</a> |
| <a href='https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Process%20Mining' target = '_blank'>IBM Process Mining</a> | Follow the instructions provided on the respective <a href='https://github.com/IBM/cp4ba-labs/tree/main/22.0.2/Process%20Mining' target = '_blank'>lab overview page</a> |
| <a href='https://github.com/IBM/cp4ba-labs/blob/main/22.0.1/Robotic%20Process%20Automation' target = '_blank'>IBM Robotic Process Automation</a> | Follow the instructions provided on the respective <a href='https://github.com/IBM/cp4ba-labs/tree/main/22.0.2/Robotic%20Process%20Automation' target = '_blank'>lab overview page</a> |

##### Lab Considerations

- The lab instructions refer to using the URLs found on the Tech Jam event page. For Jam-in-a-Box environments, please use those URLs provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful.
- The lab instructions mention how to receive your user credentials using a link on the Tech Jam event page. For Jam-in-a-Box environments, please use the admin user and admin password (or one of the business users) provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful.
- The lab instructions mostly mention to prefix your artifacts with "usrXYZ". This is important when working in a shared environment. You may choose to still follow the instructions in this point, even when this is not strictly required for the Jam-in-a-Box environment that is normally considered a single-user environment.

## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners (require an invitation) and IBMers**

To engage us, drop us a message at <a href="https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T" target="_blank">#jam-in-a-box-ba-dl</a>.

**All others**

For anyone who doesn’t fall into the business partner or IBM employee category, please feel free to open a new issue on our <a href="https://github.com/IBM/cp4ba-jam-in-a-box/issues" target="_blank">GitHub repository</a>. We’ll be more than happy to address your questions and concerns there.

## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.
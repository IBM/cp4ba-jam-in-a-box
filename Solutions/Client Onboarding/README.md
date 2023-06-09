# Client Onboarding

#### Latest Supported Cloud Pak for Business Automation Version: 22.0.2

## **Overview:**

**Introduction and solution exports:** https://github.com/IBM/cp4ba-client-onboarding-scenario 

**Assets:** The solution has [nine hands-on labs](https://github.com/IBM/cp4ba-labs/tree/main/22.0.2) associated with it.

**Jam-in-a-Box-environment:** In order to use the solution in your own Jam-in-a-Box environment, deploy the Client Onboarding solution and labs as described in [this document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/22.0.2/DeployingClientOnboarding2202.md). The document also contains hints in case you don't have access to/can't get an IBM TechZone environment.

**What's included:**

- Red Hat OpenShift (OCP 4.10) on VMWare on IBM Cloud
- IBM Cloud Pak for Business Automation 22.0.2 IF002
- IBM Process Mining 1.13.2
- IBM Robotic Process Automation 23.0.2

## Labs

Most labs are accessible using the Jam-in-a-Box environment. For some labs, you will need a separate environment. The table below provides the respective details:

**Mapping of labs to environments**

| Lab(s)                                                       | Environment (IBM TechZone - Business Partners and IBMers only) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [IBM Cloud Pak for Business Automation (End-to-End)](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/IBM%20Cloud%20Pak%20for%20Business%20Automation%20(End-to-End))<br/>[IBM Business Automation Application](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Business%20Automation%20Application)<br/>[IBM Business Automation Insights](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Business%20Automation%20Insights)<br/>[IBM FileNet Content Services](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Content)<br/>[IBM Automation Decision Services](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Decisions)<br/>[IBM Business Automation Workflow](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Workflow) | Jam-in-a-box environment (deployment instructions are availabe in this [document](https://github.com/IBM/cp4ba-client-onboarding-scenario/blob/main/22.0.2/DeployingClientOnboarding2202.md)) |
| [IBM CP4BA - Bring-up Lab](https://github.com/IBM/cp4ba-labs/blob/main/22.0.1/Bring-up) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/22.0.1/Bring-up) (CP4BA 22.0.1) |
| [IBM Process Mining](https://github.com/IBM/cp4ba-labs/blob/main/22.0.2/Process%20Mining) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/22.0.2/Process%20Mining) |
| [IBM Robotic Process Automation](https://github.com/IBM/cp4ba-labs/blob/main/22.0.1/Robotic%20Process%20Automation) | Follow the instructions provided on the respective [lab overview page](https://github.com/IBM/cp4ba-labs/tree/main/22.0.1/Robotic%20Process%20Automation) |

##### Lab Considerations

- The lab instructions refer to using the URLs found on the Tech Jam event page. For Jam-in-a-Box environments, please use those URLs provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful.
- The lab instructions mention how to receive your user credentials using a link on the Tech Jam event page. For Jam-in-a-Box environments, please use the admin user and admin password (or one of the business users) provided when the deployment completes and/or refer to the `client-onboarding-information` ConfigMap that is created when the deployment is successful.
- The lab instructions mostly mention to prefix your artifacts with "usrXYZ". This is important when working in a shared environment. You may choose to still follow the instructions in this point, even when this is not strictly required for the Jam-in-a-Box environment that is normally considered a single-user environment.
- By default the Jam-in-a-Box deployment uses an email server and an HTML-based email client that are co-deployed with CP4BA. Therefore, follow the part of the instructions in the [Client Onboarding End-to-End Demonstration](https://github.com/IBM/cp4ba-labs/tree/main/22.0.1/IBM%20Cloud%20Pak%20for%20Business%20Automation%20(End-to-End)) that refers to the local mail server/mail client.

## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners and IBMers**
To engage us, drop us a message at [#jam-in-a-box-business-automation](https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T).


**All others**
Open a new issue in this GitHub

## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

# CP4BA Demos Environment based on Apollo Business Automation/Cloud Pak Deployer for CP4BA 25.0.1

!!! IMPORTANT
>
> - As this approach relies on reserving an environment from IBM TechZone, this document is **only applicable to IBM Business Partners** that have the ability to request environments from TechZone **and IBMers**. 
> - Showcasing **RPA** in action as part of the Client Onboarding scenario requires a few manual configuration steps as described below.
> 
>If you have your own Cloud Pak for Business Automation (CP4BA) 25.0.1 environment, please refer to this [document](README_2501_SelfDeploy.md) for other options.



## Quick Start

1. Reserve a CP4BA Demos environment as described in the [section](#reserve-the-cp4ba-demos-environment) below
1. Read the [Lab Considerations](#lab-considerations) section for specifics of using the labs in the context of this CP4BA Demos environment
1. Follow the link to the documentation of the lab you want to perform in the [Lab Instructions](#lab-instructions) section



## **Overview**

This Jam-in-a-Box environment is provided to you as a cooperation between the owners of the Apollo Business Automation approach and the IBM Business Automation and Digital Labor Tiger (aka SWAT) team.

The major benefits of using this environment are:

- Environment can be used for a single-user use case and for running mini-Tech Jams with approximately 10-15 participants (feedback welcome in case you used it with more users)
- Client Onboarding scenario and lab artifacts are pre-deployed for you
- 20 business users have been created that can be given to participants of a mini-Tech Jam

!!! CAUTION
>
> It can take 5-7 hours until the environment is available.



## Reserve the CP4BA Demos Environment

Follow the journey <a href="https://techzone.ibm.com/collection/apollo-business-automation/journey-cp4ba-demos" target="_blank">Apollo Business Automation - CP4BA Demos</a> to reserve your environment on IBM TechZone. It consists of three steps:

1. Requesting the environment in step 1 and waiting till the environment is **Ready** **and fully deployed**. This will normally take approximately 5-7 hours.
   The passwords for usr001-usr020 are randomly generated.
2. Validating the successful deployment of the Cloud Pak for Business Automation as described in step 2.
3. Validating the successful deployment of the Client Onboarding scenario assets as described in step 3.

## (Optional) Reserve an RPA VM and Update the Jam-in-a-Box Single User Environment

1. Reserve your RPA environment on IBM TechZone from the <a href="https://techzone.ibm.com/collection/ibm-business-automation-traditional-and-on-premise/environments" target="_blank">IBM Business Automation - Traditional and On-Premises</a> collection by clicking on one of the **IBM Business Automation - Traditional and On-premises. V4.x** tiles
2. Fill in the reservation details and wait till the environment is **Ready**. This will normally take between 2-3 hours
3. Once your environment is **Ready**, click on the reservation in **<a href="https://techzone.ibm.com/my/reservations" target="_blank">TechZone</a>** and copy the URL shown for **RPA Asynch Server API** at the top under **Published services**
4. In your **Apollo Business Automation - CP4BA Demos** environment you need to launch the Cloud Pak Accelerator homepage in your browser. There are two different ways to do so:
      1. Construct the URL based on the following naming pattern, replacing the your-environment in the link https://cp4accelerator.apps.your-environment.ocp.techzone.ibm.com/demos with the value (e.g. console-openshift-console.apps.**66e433006794d822e0236c61**.ocp.techzone.ibm.com/) from the Desktop url from the reservation
      2. Open the **OpenShift Console**, navigate to **Networking --> Routes** and use the link under location for the **cp4accelerator-route** route and switch to the **Deploy Demo** tab

5. Click the blue **Update** button for the **Client Onboarding** tile
6. Put the value of the **RPA Asynch Server API** that you copied in step 3 into the **RPA Server** field
7. Put **cpadmin** or any other user for which the RPA bot should be invoked into the **RPA User** field
8. Finally click on the blue **Update Client Onboarding** button

!!! TIP
>
> Even after you have made the change, the value shown on the update Client Onboarding deployment page will remain to reflect the original values. That is expected, as only the runtime, not the design time values are updated while the design time values are shown.

After you have applied this configuration change the RPA bot will be invoked when you perform the Client Onboarding scenario with use **cpadmin** or the user you specified.

## Labs Instructions & Considerations

#### Lab Considerations

The lab instructions are written in context of a Tech Jam event. When performing the labs as part of Jam-in-a-Box keep in mind:

| Lab instructions mention...                                  | As part of this Jam-in-a-Box environment...                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| using the **URLs** found on the Tech Jam event page          | please login to the OpenShift console, go to **Workloads -> ConfigMaps**, and check the **000-client-onboarding-information** ConfigMap. It should appear at the top of the list.<br />The ConfigMap contains all relevant URLs for this environment. <br />For a mini-Tech Jam share them with the participants in a suitable form. |
| how to receive your **user credentials** using a link on the Tech Jam event page | please login to the OpenShift console, go to **Workloads -> ConfigMaps**, and check the **000-client-onboarding-information** ConfigMap. It should appear at the top of the list.<br />The ConfigMap contains all relevant user names and password for this environment.<br />For a mini-Tech Jam share a dedicated user name and password with each participants in a suitable form. |
| to **prefix your artifacts** with "usrXYZ"                   | depending on if you use the environment as a single-user environment or for running a mini-Tech Jam, you may choose to follow the instructions in this point. |



#### Lab Instructions

Below you find the links to the lab instructions for the labs supported in this environment:

- [IBM Cloud Pak for Business Automation (End-to-End)](../../IBM Cloud Pak for Business Automation (End-to-End)\README.md)
- [IBM Business Automation Application](../../Business Automation Application\README.md)
- [IBM Automation Decision Services](../../Decisions\README.md)
- [IBM Business Automation Insights](../../Business Automation Insights\README.md)
- [IBM Business Automation Workflow](../../Workflow\README.md)
- [IBM FileNet Content Services (CPE, GraphQL & Navigator)](../../Content\README.md)



## Support

We aim to support successfully utilizing our assets as part of Jam-in-a-Box. For questions and issues around Apollo Business Automation, please reach out to its <a href='https://techzone.ibm.com/collection/apollo-business-automation' target = '_blank'>authors</a>. 

For questions and issues around the Client Onboarding labs:

**Business Partners (require an invitation) and IBMers**

To engage us, drop us a message at <a href="https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T" target="_blank">#jam-in-a-box-ba-dl</a>.

**All others**

For anyone who doesn’t fall into the business partner or IBM employee category, please feel free to open a new issue on our <a href="https://github.com/IBM/cp4ba-jam-in-a-box/issues" target="_blank">GitHub repository</a>. We’ll be more than happy to address your questions and concerns there.



## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.

# Jam-in-a-Box - Single User Environment for CP4BA 23.0.2

!!! IMPORTANT
>
>- As this approach relies on reserving an environment from IBM TechZone, this document is **only applicable to IBM Business Partners** that have the ability to request environments from TechZone **and IBMers**. 
>- In addition, to use this environment, accessing the bastion host via **RDP** is required. Ensure you have an RDP tool of choice for your operating system.
>- Showcasing **RPA** in action as part of the Client Onboarding scenario requires a few manual configuration steps as described below.
>
>If you have your own Cloud Pak for Business Automation (CP4BA) 23.0.2 environment or can't use RDP, please refer to this [document](../../../index.md) and this [document](README_2302_SelfDeploy.md) for other options.



## Quick Start

1. Reserve and prepare the Jam-in-a-Box environment as described in the [section](#reserve-and-prepare-the-jam-in-a-box-single-user-environment) below
1. Read the [Lab Considerations](#lab-considerations) section for specifics of using the labs in the context of this Jam-in-a-Box environment
1. Follow the link to the documentation of the lab you want to perform in the [Lab Instructions](#lab-instructions) section



## **Overview**

This Jam-in-a-Box environment is provided to you by the IBM Business Automation and Digital Labor SWAT team.

The major benefits of using this environment are:

- Provisioning time is only 2-3 hours
- Client Onboarding scenario and lab artifacts are pre-deployed for you
- All links and user credentials are stored for you in Firefox

Based on the technology used to achieve a short provisioning time, you need to perform a few simple steps before you can use the environment.

**What's included:**

- Red Hat OpenShift (OCP 4.12) on VMWare on IBM Cloud
- IBM Cloud Pak for Business Automation 23.0.2 IF002



## Reserve and Prepare the Jam-in-a-Box Single User Environment

1. Reserve your environment on IBM TechZone from the <a href="https://techzone.ibm.com/collection/ibm-cloud-pak-for-business-automation-and-digital-labor-jam-in-a-box/environments" target="_blank">IBM Cloud Pak for Business Automation and Digital Labor - Jam-in-a-Box</a> collection by clicking on the **Jam in a Box - Single-User** tile

      On the **Create a reservation** page make the following selections:

      - **Purpose**: e.g. Education
      - **Purpose description**: Enter any text<br/>
      **Tip:** The selection you make here determines if you need to specify a 'Sales Opportunity number' and the 'reservation policy' (how long the environment is available and how often it can be extended).
      - **Preferred Geography**: Select the geography that is closest to you. <br/>
      **Remark:** Depending on available capacity the deployment have been seen to fail sometimes. Please request another environment, potentially selecting a different geography.
      - **End date and time**: Should get populated automatically. No changes needed.
      - **Accept the terms and conditions**: In the lower right corner, check the box 
      - **Submit**

2. Wait till the environment is **Ready**, this will normally take between 2-3 hours

3. Once your environment is Ready, connect to the bastion host through **RDP** (open the reserved environment from **<a href="https://techzone.ibm.com/my/reservations" target="_blank">https://techzone.ibm.com/my/reservations</a>** and copy the RDP value at the top to your RDP tool)
   **Important:** The credentials to login to the bastion host are mention in the description of the tile. You may need to click a little twisty icon to see the full description with the credentials that are mentioned at the bottom.

   For hints on how to access the bastion host via RDP for Windows and Mac, refer to this [document](AccessingBastionHostViaRDP.md).

4. From within the bastion host

      1. **Open** **Firefox** using the icon on the desktop
      2. **Open** the **Red Hat OpenShift console** by clicking the **Red Hat OpenShift bookmark**
      3. **Login** to the Red Hat OpenShift console using the credentials for the user **ocadmin** that are stored in Firefox
      4. Copy the **login command** to the clipboard 
         (Under "ocadmin" in the top right corner click **Copy login command**, a new tab opens, log in again using **ocadmin**, click **Display Token**, and then copy the entire line under **Log in with this token**)
      5. Open a **Terminal** using the respective icon on the desktop, **paste the content from the clipboard** (right click on the Terminal window, then select "Paste"), and press **Enter** to login to your Red Hat OpenShift cluster from the command line
      6. Type **./31-prepareJiaB4usage.sh** (including the dot) at the beginning) and press **Enter** to execute the script that prepares the environment for usage
      7. When the script asks you if you want to continue, enter **y** (or Y or Yes or YES) and press **Enter**
      8. Once the script completes, your environment is ready to be used for the supported labs. Follow the respective lab instructions for the next steps


!!! IMPORTANT
>
> It might happen that:
>
> - the login does not work, or shows "Error 502 - Bad Gateway". In this case please wait for some more time (about 15 minutes), then the log-in should work and the requested page is shown
> - the login results in "404 Page not found" error.  In this case please wait for some more time, then the log-in should work and the requested page is shown
>
> These issues are the result of restarting some pods, which may take a different amount of time depending on the resources available on TechZone.

## Reserve RPA VM and Update the Jam-in-a-Box Single User Environment

1. Reserve your RPA environment on IBM TechZone from the <a href="https://techzone.ibm.com/collection/ibm-business-automation-traditional-and-on-premise/environments" target="_blank">IBM Business Automation - Traditional and On-Premises</a> collection by clicking on one of the **IBM Business Automation - Traditional and On-premises. V4.3** tiles
2. Fill in the reservation details and wait till the environment is **Ready**. This will normally take between 2-3 hours
3. Once your environment is **Ready**, click on the reservation in **<a href="https://techzone.ibm.com/my/reservations" target="_blank">TechZone</a>** and copy the URL shown for **RPA Asynch Server API** at the top under **Published services**
4. In your **Jam-in-a-Box - Single-User environment**, open a browser and click on the **IBM BA Studio** bookmark
5. From the top-left hamburger menu select **Business Automation**
6. On the left click on **Workflow** and then on the tile **Client Onboarding** on the right (don't click the open link)
7. Click on the **three dots** next to the blue open button and select **Open in Process Designer**
8. Select **Environment variables** as part of the Workflow automation settings 
9. Scroll down to the variables **rpaBotExecutionUser** and **rpaServer**
10. For **rpaBotExecutionUser** set the value to **cp4badmin**
11. For **rpaServer** set the value to the value you copied previously from **RPA Asynch Server API**
12. Click on the **round checkmark icon** with a small 1 in the top right corner and click on **Business automations** in the bread crump

After you have manually applied this configuration change the RPA bot will be invoked when you perform the Client Onboarding scenario with use **cp4badmin**.

## Labs Instructions & Considerations

#### Lab Considerations

The lab instructions are written in context of a Tech Jam event. When performing the labs as part of Jam-in-a-Box keep in mind:

| Lab instructions mention...                                  | As part of this Jam-in-a-Box environment...                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| using the **URLs** found on the Tech Jam event page          | please use the **bookmarks** created for you in **Firefox**  |
| how to receive your **user credentials** using a link on the Tech Jam event page | please use the **credentials stored** within **Firefox** for either the admin user **cp4badmin** or the business user **usr001** |
| to **prefix your artifacts** with "usrXYZ"                   | you may choose to still follow the instructions in this point, even when this is not strictly required as this is a single-user environment |

!!! TIP
>
> Initially the environment may appear a little slow. Once the components have warmed up, it should perform reasonably well.

#### Lab Instructions

Below you find the links to the lab instructions for the labs supported in this environment:

- [IBM Cloud Pak for Business Automation (End-to-End)](../../IBM Cloud Pak for Business Automation (End-to-End)\README.md)
- [IBM Business Automation Application](../../Business Automation Application\README.md)
- [IBM Automation Decision Services](../../Decisions\README.md)
- [IBM Automation Document Processing](../../Document Processing\README.md)
- [IBM Business Automation Insights](../../Business Automation Insights\README.md)
- [IBM Business Automation Workflow](../../Workflow\README.md)
- [IBM FileNet Content Services (CPE, GraphQL & Navigator)](../../Content\README.md)



## Support

We aim to support successfully utilizing our Jam-in-a-Box.

**Business Partners (require an invitation) and IBMers**

To engage us, drop us a message at <a href="https://ibm-cloudpak-partners.slack.com/archives/C04SMFNLA3T" target="_blank">#jam-in-a-box-ba-dl</a>.

**All others**

For anyone who doesn’t fall into the business partner or IBM employee category, please feel free to open a new issue on our <a href="https://github.com/IBM/cp4ba-jam-in-a-box/issues" target="_blank">GitHub repository</a>. We’ll be more than happy to address your questions and concerns there.



## Disclaimer

The information, tools, and artifacts describes and linked are provided AS-IS and without any warranty. Please also refer to the license that is part of this repository for details.
# ProgrammaticExportSampleAppISV

This is a sample app which shocases how to integrate with the Microsoft CMP partner analytics **Programmatic Access APIs**. The APIs allow you to easily schedule custom reports and ingest key data sets into your internal analytics systems.

## Prerequisites

- **Commercial Marketplace enrollment**: You should be enrolled in Commercial Marketplace program and have a Partner Center account to access Commercial Marketplace Analytics data in a programmatic manner. See  [this article](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/create-account)  to learn more on how to enroll into the commercial marketplace program in Partner Center.
    
- **Creating Azure Active Directory (AAD) application**: Regular user credentials cannot be used for programmatic access of Commercial Marketplace Analytics data. An Azure AD (AAD) application needs to be created along with a secret to access the programmatic access APIs. The steps for creating an AAD application and secret is listed in this  [link](https://docs.microsoft.com/en-us/azure/active-directory/develop/quickstart-register-app?toc=/azure/active-directory/azuread-dev/toc.json&bc=/azure/active-directory/azuread-dev/breadcrumb/toc.json).

## What does this sample app do?
- The main aim of this app is to demonstrate how the **Programmatic Access APIs** can be programmatically called.
- This is a very simple .NET core app which exposes a controller and a simple UI to call the controllers.
- You can check the controller code to see how **Programmatic Access APIs** need to be called.
- As of now, you can do the following in the sample app:
    1. Schedule reports
    2. View system queries and user defined queries
    3. Create custom queries
    4. Create custom queries

## Steps to run the app locally:
- Open the appsettings.Development.json file and provide the following parameters:
    1. TenantId
    2. WebAppClientId
    3. WebAppClientSecret
- Running the project will start the server and launch the UI page.

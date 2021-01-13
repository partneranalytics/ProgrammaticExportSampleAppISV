ProgrammaticExportSampleAppISV

This is a sample app which shocases how to integrate with the Programmatic Access APIs which allows you to easily schedule custom reports and ingest key data sets into your internal analytics systems.

Prerequisites:

1. Commercial Marketplace enrollment: You should be enrolled in Commercial Marketplace program and have a Partner Center account to access Commercial Marketplace Analytics data in a programmatic manner. See <a href="https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/create-account">this article</a> to learn more on how to enroll into the commercial marketplace program in Partner Center. 

2. Creating Azure Active Directory (AAD) application: Regular user credentials cannot be used for programmatic access of Commercial Marketplace Analytics data. An Azure AD (AAD) application needs to be created along with a secret to access the programmatic access APIs. The steps for creating an AAD application and secret is listed in this <a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/quickstart-register-app?toc=/azure/active-directory/azuread-dev/toc.json&bc=/azure/active-directory/azuread-dev/breadcrumb/toc.json">link</a>.

Steps:

1. Open the appsettings.Development.json file and provide the following parameters:<br />
    a. TenantId<br />
    b. WebAppClientId<br />
    c. WebAppClientSecret

2. Run the project
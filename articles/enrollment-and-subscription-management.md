Copyright

Monday, January 15, 2018

10:31 AM

 

Copyright

The information contained in this document represents the current view
of Microsoft Corporation on the issues discussed as of the date of
publication. Because Microsoft must respond to changing market
conditions, it should not be interpreted to be a commitment on the part
of Microsoft, and Microsoft cannot guarantee the accuracy of any
information presented after the date of publication.

MICROSOFT MAKES NO WARRANTIES, EXPRESS, IMPLIED OR STATUTORY, AS TO THE
INFORMATION IN THIS DOCUMENT.

Complying with all applicable copyright laws is the responsibility of
the user. Without limiting the rights under copyright, no part of this
document may be reproduced, stored in or introduced into a retrieval
system, or transmitted in any form or by any means (electronic,
mechanical, photocopying, recording, or otherwise), or for any purpose,
without the express written permission of Microsoft Corporation.

Microsoft may have patents, patent applications, trademarks, copyrights,
or other intellectual property rights covering subject matter in this
document. Except as expressly provided in any written license agreement
from Microsoft, the furnishing of this document does not give you any
license to these patents, trademarks, copyrights, or other intellectual
property.

The descriptions of other companies' products in this document, if any,
are provided only as a convenience to you. Any such references should
not be considered an endorsement or support by Microsoft. Microsoft
cannot guarantee their accuracy, and the products may change over time.
Also, the descriptions are intended as brief highlights to aid
understanding, rather than as thorough coverage. For authoritative
descriptions of these products, please consult their respective
manufacturers.

© 2018 Microsoft Corporation. All rights reserved. Any use or
distribution of these materials without express authorization of
Microsoft Corp. is strictly prohibited.

Microsoft, Azure, Active Directory, Office 365, SharePoint, Windows,
Microsoft Intune, Windows PowerShell, Windows Server, and Xbox Live are
either registered trademarks of Microsoft Corporation in the United
States and/or other countries.

The names of actual companies and products mentioned herein may be the
trademarks of their respective owners.

 

 

Outstanding Items

December 19, 2017

7:47 AM

 

 

0\. Enrollment and Subscription Management

Tuesday, December 12, 2017

9:33 AM

V1.0 Draft

 
=

Overview
========

 

Any Microsoft customer with a Microsoft Enterprise Agreement can add
Azure to their agreement. This is done by making an upfront monetary
commitment to Azure. That commitment is used over the course of the year
as Azure services are consumed.

 

This guide is focused on Enterprise customers that have made a
commitment as part of their assumes the organization has made its
commitment to Azure through following a corporate procurement process.

The following enrollment approach **allows an organization to be
flexible** in designing its Azure hierarchy in a way that best
represents the organization's operating model and taking into **account
billing, resource access and organizational structure**.

 

The approach includes:

 

1.  **[Account/Enterprise
    > Agreement](onenote:#1.%20Account\Enterprise%20Agreement&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={A0EF3D72-D0D5-45BC-BDF7-F5F27623EF86}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):**
    > Define the Azure Enterprise Administrative roles

2.  [**Subscriptions**](onenote:#2.%20Subscriptions&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={6426C451-B3CC-436F-8110-CB948DDD3AF9}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Once the roles are defined, you design your subscription model

3.  [**Resource
    > Groups**](onenote:#3.%20Resources%20Groups&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={1B2519F5-B81D-41E3-B9AC-310A1B283B95}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Design the resource groups which logically group resources that
    > are alike and/or by function, and/or by geography and/or by
    > workload

4.  [**Naming Standards and
    > Tags**](onenote:#4.%20Naming%20Standards%20and%20Tags&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={4D322F24-C16B-41F2-84E7-E2E883E04833}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > to cohesively categorize Azure resources for the purpose of
    > security auditing, chargeback, and show-back

5.  [**Resource Policies &
    > Locks**](onenote:#5.%20Resource%20Policies%20%20Locks&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={AD0DDA49-0776-4D62-AEDA-CECF6DAEFC15}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > These are the governance controls that regulate how organizations
    > manage their Azure resources

6.  [**Role-based access Control
    > (RBAC)**](onenote:#6.%20Role-based%20Access%20Control%20(RBAC)&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={41D957D8-E5EA-4217-BC3D-F87C799A7163}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > who can do what and where \-\-- Azure permissions

 

![Machine generated alternative text: Account /Enterprise Agreement
Subscriptions Resource Groups Naming Standards and Tags Resource
Policies & Locks RBAC ](media/image1.png){width="14.822916666666666in"
height="9.666666666666666in"}

 

Next Steps
==========

1.  [Account/Enterprise
    > Agreement](onenote:#1.%20Account\Enterprise%20Agreement&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={A0EF3D72-D0D5-45BC-BDF7-F5F27623EF86}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Understand the roles and portals required for Azure administration
    > and governance

 

Additional Information
======================

-   [Licensing Azure for the
    > enterprise](https://azure.microsoft.com/en-us/pricing/enterprise-agreement/)

>  

MICROSOFT MAKES NO WARRANTIES, EXPRESS OR IMPLIED, IN THIS DOCUMENT.  

Complying with all applicable copyright laws is the responsibility of
the user.  Without limiting the rights under copyright, no part of this
document may be reproduced, stored in or introduced into a retrieval
system, or transmitted in any form or by any means (electronic,
mechanical, photocopying, recording, or otherwise), or for any purpose,
without the express written permission of Microsoft Corporation.  

Microsoft may have patents, patent applications, trademarks, copyrights,
or other intellectual property rights covering subject matter in this
document.  Except as expressly provided in any written license agreement
from Microsoft, our provision of this document does not give you any
license to these patents, trademarks, copyrights, or other intellectual
property.  

The descriptions of other companies' products in this document, if any,
are provided only as a convenience to you.  Any such references should
not be considered an endorsement or support by Microsoft.  Microsoft
cannot guarantee their accuracy, and the products may change over time.
Also, the descriptions are intended as brief highlights to aid
understanding, rather than as thorough coverage. For authoritative
descriptions of these products, please consult their respective
manufacturers. 

© 2017 Microsoft Corporation. All rights reserved. Any use or
distribution of these materials without express authorization of
Microsoft Corp. is strictly prohibited. 

Microsoft and Windows are either registered trademarks or trademarks of
Microsoft Corporation in the United States and/or other countries. 

The names of actual companies and products mentioned herein may be the
trademarks of their respective owners. 

 

 

1\. Account/Enterprise Agreement

Tuesday, December 12, 2017

9:11 AM

 

V1.0 Draft

 
=

Description
===========

>  
>
> An organization's Microsoft **enterprise agreement** is the
> cornerstone of an organization\'s Azure administration and governance
> and allows for subdivisions into **Azure Departments, Azure Accounts,
> and Azure Subscriptions**.
>
>  
>
> The hierarchy design is an important component in the billing
> reporting discussing in the operations section. While it is not fixed,
> it can become challenging to change the structure as workloads are
> deployed, it is important to include the appropriate stakeholders
> during the design process and run through different usage scenarios.
>
>  
>
> ![Machine generated alternative text: Enterprise Administrator (2)
> Enterprise Enrollment Department Administrator (2) Department Account
> Owner(l) Account Subscription Service Administrator(n) Account
> Subscription Department Account Subscription Subscription
> ](media/image2.png){width="17.083333333333332in"
> height="7.520833333333333in"}
>
>  
>
> To administer your Microsoft Azure services under your enrollment,
> there are **4 distinct administrative roles** and the associated
> **Azure portals**:

  **Administrative Role**        **Portal**
  ------------------------------ ----------------------------------------------
  **Enterprise Administrator**   [Enterprise Portal](https://ea.azure.com)
  **Department Administrator**   [Enterprise Portal](https://ea.azure.com)
  **Account Owner**              [Account Portal](http://account.azure.com)
  **Service Administrator**      [Management Porta](http://portal.azure.com)l

>  

Proven Practices
================

 

> The **Enterprise Administrator** account is the first account created
> at on-boarding and has **full access and visibility into all activity
> and resources of a corporate enrollment**.
>
>  
>
> **Two people** should be assigned this responsibility resulting in the
> following benefits;
>
>  

-   **Segregation of Duties (SoD): **

    -   SoD is a basic internal control that attempts to ensure that no
        > single individual has the authority to execute two or more
        > conflicting sensitive transactions. The purpose is to prevent
        > or reduce the risk of error or changes impacting the
        > infrastructure.

-   **Staff Redundancy; **

    -   By assigning a primary and backup service continuity can be
        > ensured if the primary contract is not available.

    -   If enterprise-wide decisions need to be made the approval must
        > come from both people

-   **Prevent Collusion;**

    -   Given the appropriate assignment of the responsibility it will
        > be difficult to achieve agreement between the two to proceed
        > with an unplanned or unlawful activity.

 

Next Steps
==========

1.  [Enterprise
    > Administrators](onenote:#1.1%20Enterprise%20Enrollment&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={BC0ED44A-7629-41AD-A121-D4D4304841F6}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one);
    > Activate enrollment and assign enterprise administrators

2.  [Department
    > Administrators](onenote:#1.2%20Departments&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={53AE0263-490E-460A-AFE6-C88B3CF42304}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one);
    > Select a department model, create initial departments and assign
    > administrators

3.  [Account
    > Owners](onenote:#1.3%20Accounts&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={482CCEB4-ADC8-490D-9662-318BA2C25BCB}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one);
    > Select an account model, create accounts and assign account owners

4.  [Service
    > Administrators](onenote:#1.4%20Service%20Administrator%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={B8E8D99D-245A-4A1A-BBB3-E1FDAAADF292}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Assign service administrators

5.  [Governing Privileged
    > Accounts](onenote:#1.5%20Governing%20Privileged%20Accounts%20Across%20Azure%20Portals&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={A9C7429F-EC2B-4C7E-8CF4-14B9CB9DB8D4}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Understand how to managed access to Azure privileged
    > administration accounts.

 

Additional Information
======================

 

-   [Onboarding Guide to the Microsoft Azure Enterprise Portal (Direct
    > Enrollment)](https://eaportalonboardingvideos.blob.core.windows.net/onboardingvideos/AzureDirectEACustomerOnboardingGuide_En.pdf)

 

MICROSOFT MAKES NO WARRANTIES, EXPRESS OR IMPLIED, IN THIS DOCUMENT.  

Complying with all applicable copyright laws is the responsibility of
the user.  Without limiting the rights under copyright, no part of this
document may be reproduced, stored in or introduced into a retrieval
system, or transmitted in any form or by any means (electronic,
mechanical, photocopying, recording, or otherwise), or for any purpose,
without the express written permission of Microsoft Corporation.  

Microsoft may have patents, patent applications, trademarks, copyrights,
or other intellectual property rights covering subject matter in this
document.  Except as expressly provided in any written license agreement
from Microsoft, our provision of this document does not give you any
license to these patents, trademarks, copyrights, or other intellectual
property.  

The descriptions of other companies' products in this document, if any,
are provided only as a convenience to you.  Any such references should
not be considered an endorsement or support by Microsoft.  Microsoft
cannot guarantee their accuracy, and the products may change over time.
Also, the descriptions are intended as brief highlights to aid
understanding, rather than as thorough coverage. For authoritative
descriptions of these products, please consult their respective
manufacturers. 

© 2017 Microsoft Corporation. All rights reserved. Any use or
distribution of these materials without express authorization of
Microsoft Corp. is strictly prohibited. 

Microsoft and Windows are either registered trademarks or trademarks of
Microsoft Corporation in the United States and/or other countries. 

The names of actual companies and products mentioned herein may be the
trademarks of their respective owners. 

 

 

2.0 Subscriptions

Tuesday, December 12, 2017

9:35 AM

 

Description
===========

A **Subscription** is a ***logical limit of scale*** by which resources
can be allocated. These limits include hard and soft caps of various
resource types (for example, 10,000 compute cores per region per
subscription in the Azure Resource Manager model).

***Scalability and complexity are a key element*** for understanding how
the subscription strategy will account for growth as consumption
increases.

A subscription additionally forms a top-level ***billing unit***.

 

 

![Machine generated alternative text: Account /Enterprise Agreement
Subscriptions Resource Groups Naming Standards and Tags Resource
Policies & Locks RBAC ](media/image1.png){width="14.822916666666666in"
height="9.666666666666666in"}

>  

Design Considerations
=====================

 

-   Take subscription limits under consideration when planning for
    > subscription designs. See subscription limits at:
    > <https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits>

 

-   When planning to have multiple Azure subscriptions, consider the
    > complexity implications including:

 

-   Duplicate provisioning and management: IP Address space, network
    > circuits, gateways, vNets, Subnets, NSGs, routing

-   More connectivity to manage

-   More security to manage

-   More identities to manage

-   Potentially more ExpressRoute (ER) circuits to buy

 

Proven Practices
================

-   Plan for multiple subscriptions

-   Start with one subscription; try to minimize the number of
    > subscriptions; add additional subscriptions based on requirements

-   Minimize the number of subscription owners

-   Refrain from assigning one account owner across multiple
    > subscription types

-   Use Azure Active Directory for Azure Governance roles

-   Use Built-In Roles before Custom Roles

-   Create Custom RBAC Roles only if Built-in does not exist

-   Use groups to assign RBAC versus users

-   Take network requirements and Express Route boundaries into account

 

 

 

Next Steps
==========

1.  [Subscription
    > Guide](onenote:#1.4%20Subscription%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={C956FEBD-EC6A-4877-B5CB-FAB9E5D3494C}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > define the subscription model, create subscriptions, and assign
    > service administrators.

2.  [Resources
    > Groups](onenote:#3.%20Resources%20Groups&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={1B2519F5-B81D-41E3-B9AC-310A1B283B95}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Understand resource groups.

3.  [Resource Group
    > Guide](onenote:#3.1%20Resource%20Group%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={2AC7027D-425B-4E49-8277-74839996B14B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > define the resource group model and create resource groups.

4.  [Naming Standards and
    > Tags](onenote:#4.%20Naming%20Standards%20and%20Tags&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={4D322F24-C16B-41F2-84E7-E2E883E04833}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > understand naming conventions

5.  [Azure Tags
    > Guide](onenote:#4.1%20Azure%20Tags%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={56A9DB2F-CE2A-428A-959B-B73AF1698066}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > apply tags to resources

6.  [Resources
    > Groups](onenote:#3.%20Resources%20Groups&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={1B2519F5-B81D-41E3-B9AC-310A1B283B95}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Understand resource groups.

7.  [Resource Group
    > Guide](onenote:#3.1%20Resource%20Group%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={2AC7027D-425B-4E49-8277-74839996B14B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > define the resource group model and create resource groups.

8.  [Resource Policies &
    > Locks](onenote:#5.%20Resource%20Policies%20%20Locks&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={AD0DDA49-0776-4D62-AEDA-CECF6DAEFC15}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > understand resource policies and locks

9.  [Resource Policy
    > Guide](onenote:#5.1%20Resource%20Policy%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={8E2F169A-92DF-46ED-97E3-2F0BA82EC91A}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create and apply resource policies

10. [Resource Locks
    > Guide](onenote:#5.2%20Resource%20Locks%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={E66C50A2-F1B0-4DF5-A582-2B7C6781439B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create resource locks

11. [Role-based Access Control
    > (RBAC)](onenote:#6.%20Role-based%20Access%20Control%20(RBAC)&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={41D957D8-E5EA-4217-BC3D-F87C799A7163}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > learn about Azure RBAC

12. [Azure Roles
    > Guide](onenote:#6.1%20Azure%20Roles%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={92943F76-474F-4382-8A19-0EF585B75266}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > apply roles

 

>  

 

Links
=====

-   [Azure enterprise scaffold - prescriptive subscription
    > governance](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-subscription-governance)

>  

 

![C:\\EFAC62E5\\2387C7B1-13D0-4026-92CB-129924B69776\_files\\image003.png](media/image3.png){width="15.041666666666666in"
height="1.8541666666666667in"}

 

 

3\. Resources Groups

Tuesday, December 12, 2017

9:36 AM

 

Description
===========

 

A **Resource Group** is a logical container that allows you to
categorize your resources. Examples include: billing, security, web
servers, compute resources, and applications. Resource groups are also
used for access control.

 

 

![Machine generated alternative text: Account /Enterprise Agreement
Subscriptions Resource Groups Naming Standards and Tags Resource
Policies & Locks RBAC ](media/image1.png){width="14.822916666666666in"
height="9.666666666666666in"}

 

 

 

Design Considerations
=====================

 

-   All the resources in your group should share the same lifecycle. You
    > deploy, update, and delete them together. If one resource, such as
    > a database server, needs to exist on a different deployment cycle
    > it should be in another resource group

-   Resources mandatorily belong to a single resource group

-   A resource group can contain resources that reside in different
    > regions.

-   A resource group is tied to a subscription: a resource group cannot
    > span subscriptions; once you assign a resource to a resource
    > group, you can move it out, but it can\'t span multiple
    > subscriptions.

-   A resource can interact with resources in other resource groups.
    > This interaction is common when the two resources are related but
    > do not share the same lifecycle (for example, web apps connecting
    > to a database).

-   A resource group can be used to scope access control for
    > administrative actions. You can apply RBAC permissions at the
    > subscription level or at the resource group level. Anything
    > assigned at the subscription level will be inherited at the
    > resource group level.

>  

 

Proven Practices
================

 

-   The resource group design should follow Agile IT workload designs
    > which include: Web tier, application tier, data tier, management
    > tier.

-   Assign permissions at the resource group level as opposed to
    > assigning them at the subscription level.

-   Use
    > [tagging](onenote:#4.1%20Azure%20Tags%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={56A9DB2F-CE2A-428A-959B-B73AF1698066}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one)
    > within your resource groups to ensure categorization of resources
    > for billing and security purposes.

-   Use a cohesive and consistent naming standard of your security
    > groups across your subscriptions

-   When creating resource groups, ensure that specific tiers (web, app,
    > data, management) of the workload are assigned to the same region.

 

Next Steps
==========

 

1.  [Resource Group
    > Guide](onenote:#3.1%20Resource%20Group%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={2AC7027D-425B-4E49-8277-74839996B14B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > define the resource group model and create resource groups.

2.  [Naming Standards and
    > Tags](onenote:#4.%20Naming%20Standards%20and%20Tags&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={4D322F24-C16B-41F2-84E7-E2E883E04833}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > understand naming conventions

3.  [Azure Tags
    > Guide](onenote:#4.1%20Azure%20Tags%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={56A9DB2F-CE2A-428A-959B-B73AF1698066}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > apply tags to resources

4.  [Resources
    > Groups](onenote:#3.%20Resources%20Groups&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={1B2519F5-B81D-41E3-B9AC-310A1B283B95}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Understand resource groups.

5.  [Resource Group
    > Guide](onenote:#3.1%20Resource%20Group%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={2AC7027D-425B-4E49-8277-74839996B14B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > define the resource group model and create resource groups.

6.  [Resource Policies &
    > Locks](onenote:#5.%20Resource%20Policies%20%20Locks&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={AD0DDA49-0776-4D62-AEDA-CECF6DAEFC15}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > understand resource policies and locks

7.  [Resource Policy
    > Guide](onenote:#5.1%20Resource%20Policy%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={8E2F169A-92DF-46ED-97E3-2F0BA82EC91A}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create and apply resource policies

8.  [Resource Locks
    > Guide](onenote:#5.2%20Resource%20Locks%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={E66C50A2-F1B0-4DF5-A582-2B7C6781439B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create resource locks

9.  [Role-based Access Control
    > (RBAC)](onenote:#6.%20Role-based%20Access%20Control%20(RBAC)&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={41D957D8-E5EA-4217-BC3D-F87C799A7163}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > learn about Azure RBAC

10. [Azure Roles
    > Guide](onenote:#6.1%20Azure%20Roles%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={92943F76-474F-4382-8A19-0EF585B75266}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > apply roles

 

 

Links
=====

<https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-overview#resource-groups>

<https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-portal>

 

 

 

![C:\\EFAC62E5\\2387C7B1-13D0-4026-92CB-129924B69776\_files\\image004.png](media/image4.png){width="15.354166666666666in"
height="1.7708333333333333in"}

 

 

4\. Naming Standards and Tags

Tuesday, December 12, 2017

9:36 AM

 

Description
===========

 

This section refers to the common standards and practices to use when
designing naming standards and tags in Azure.

 

You apply tags to your Azure resources to logically organize them by
categories. Each tag consists of a name and a value.

 

For example, you can apply the name \"Environment\" and the value
\"Production\" to all the resources in production. Without this tag, you
might have difficulty identifying whether a resource is intended for
development, test, or production. However, \"Environment\" and
\"Production\" are just examples. You define the names and values that
make the most sense for organizing your subscription.

 

 

![Machine generated alternative text: Account /Enterprise Agreement
Subscriptions Resource Groups Naming Standards and Tags Resource
Policies & Locks RBAC ](media/image1.png){width="14.822916666666666in"
height="9.666666666666666in"}

 

 

Design Considerations
=====================

 

Naming Conventions
------------------

 

The choice of a name for any resource in Microsoft Azure is important
because: 

-   Follow Azure [naming rules and
    > restrictions](https://docs.microsoft.com/en-us/azure/architecture/best-practices/naming-conventions#naming-rules-and-restrictions)

-   It is difficult to change a name later.

-   Names must meet the requirements of their specific resource type.

-   Some types of resources require additional care for [naming
    > conventions](https://docs.microsoft.com/en-us/azure/architecture/best-practices/naming-conventions#naming-rules-and-restrictions)

 

Tags
----

 

The following limitations apply to tags:

 

-   Each resource or resource group can have a maximum of 15 tag
    > name/value pairs. This limitation applies only to tags directly
    > applied to the resource group or resource. A resource group can
    > contain many resources that each have 15 tag name/value pairs.

-   The tag name is limited to 512 characters, and the tag value is
    > limited to 256 characters. For storage accounts, the tag name is
    > limited to 128 characters, and the tag value is limited to 256
    > characters.

-   Tags applied to the resource group are not inherited by the
    > resources in that resource group.

>  

If you have more than 15 values that you need to associate with a
resource, use a JSON string for the tag value. The JSON string can
contain many tag values.

 

 

Proven Practices
================

 

Naming Conventions
------------------

-   When naming Azure subscriptions, verbose names make understanding
    > the context and purpose of each subscription clear. When working
    > in an environment with many subscriptions, following a shared
    > naming convention can improve clarity

A recommended pattern for naming subscriptions is:

\<Company\> \<Department (optional)\> \<Product Line (optional)\>
\<Environment\>

An example of subscription naming approach:

  **Department**   **Product Line or Service**   **Environment**   **Full Name**
  ---------------- ----------------------------- ----------------- --------------------------------------------------
  Marketing        Social Analytics Service      Production        Corp Marketing SociaAnalitycs Service Production

 

 

 

Tags
----

-   Use Azure resource policies to apply and enforce mandatory tags
    > across your subscriptions and resource groups to avoid deployment
    > of resources without the required tags

-   Leverage Tags for purposes of billing monitoring and reporting

-   Leverage Tags for security and inventory of resources

 

 
-

Next Steps
==========

 

1.  [Azure Tags
    > Guide](onenote:#4.1%20Azure%20Tags%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={56A9DB2F-CE2A-428A-959B-B73AF1698066}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > apply tags to resources

2.  [Resources
    > Groups](onenote:#3.%20Resources%20Groups&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={1B2519F5-B81D-41E3-B9AC-310A1B283B95}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > Understand resource groups.

3.  [Resource Group
    > Guide](onenote:#3.1%20Resource%20Group%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={2AC7027D-425B-4E49-8277-74839996B14B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > define the resource group model and create resource groups.

4.  [Resource Policies &
    > Locks](onenote:#5.%20Resource%20Policies%20%20Locks&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={AD0DDA49-0776-4D62-AEDA-CECF6DAEFC15}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > understand resource policies and locks

5.  [Resource Policy
    > Guide](onenote:#5.1%20Resource%20Policy%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={8E2F169A-92DF-46ED-97E3-2F0BA82EC91A}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create and apply resource policies

6.  [Resource Locks
    > Guide](onenote:#5.2%20Resource%20Locks%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={E66C50A2-F1B0-4DF5-A582-2B7C6781439B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create resource locks

7.  [Role-based Access Control
    > (RBAC)](onenote:#6.%20Role-based%20Access%20Control%20(RBAC)&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={41D957D8-E5EA-4217-BC3D-F87C799A7163}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > learn about Azure RBAC

8.  [Azure Roles
    > Guide](onenote:#6.1%20Azure%20Roles%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={92943F76-474F-4382-8A19-0EF585B75266}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > apply roles

 

 

 

Links and References
====================

<https://docs.microsoft.com/en-us/azure/architecture/best-practices/naming-conventions>

<https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-using-tags>

![C:\\EFAC62E5\\2387C7B1-13D0-4026-92CB-129924B69776\_files\\image005.png](media/image5.png){width="14.791666666666666in"
height="1.5416666666666667in"}

 

 

5\. Resource Policies & Locks

Tuesday, December 12, 2017

9:37 AM

Description
===========

 

An **Azure Resource Manager Policy** is a service in Azure that you use
to create, assign and, manage policy definitions. Policy definitions
enforce different rules and actions over your resources to ensure they
compliant with organizational standards and service level agreements.

 

Resource locks allows organizations to lock a subscription, resource
group, or resource to prevent other roles in the organization from
inadvertently deleting or modifying critical resources.

 

![Machine generated alternative text: Account /Enterprise Agreement
Subscriptions Resource Groups Naming Standards and Tags Resource
Policies & Locks RBAC ](media/image1.png){width="14.822916666666666in"
height="9.666666666666666in"}

 

 
=

Design Considerations
=====================

-   It is important to keep organizational hierarchies in mind when
    > creating definitions and assignments. We recommend creating policy
    > definitions at a higher level, for example at the management group
    > or subscription level, and assigning at the next child level. For
    > example, if you create a policy definition at the management group
    > level, a policy assignment of that definition can be scoped down
    > to a subscription level within that management group. 

-   In order to apply policies across subscriptions, one must have
    > permissions across said subscriptions.

-   Plan how you will deal with policy exceptions

 

Proven Practices
================

Resource Policies
-----------------

>  

-   If you are creating policy definitions in your environment, we
    > recommend starting with an audit effect, as opposed to a deny
    > effect, to keep track of the impact of your policy definition on
    > the resources in your environment. For example, if you have
    > scripts already in place to autoscale up your applications,
    > setting a deny effect may hinder those automations tasks you
    > already have in place.  

-   We encourage using the standard pricing tier, to better understand
    > the compliance state of your environment. For more information
    > about our pricing models and what each of them offer, take a look
    > at [Pricing](https://azure.microsoft.com/pricing/details/azure-policy).  

-   We recommend always using initiative definitions instead of policy
    > definitions, even if you only have one policy in mind. For
    > example, if you have a policy definition -- policyDefA and you
    > create it under the initiative definition - initiativeDefC, if you
    > decide to create another policy definition later
    > for policyDefB with goals similar to that of policyDefA, you can
    > add it under initiativeDefC and track them better that way.

-   Apply policies that map to organizational compliance, operational
    > and security requirements.

-   Have a process that justifies exceptions to policies

 

Resource Locks
--------------

-   Resource locks allow you to prevent unwanted or accidental changes
    > or deletion to a resource.

-   Before resource locks are used, proper planning for objects and
    > operational process for creating and removing locks need to be
    > established.

-   Use resource locks for objects that are mostly static from a
    > configuration perspective.

 

Next Steps
==========

1.  [Resource Policy
    > Guide](onenote:#5.1%20Resource%20Policy%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={8E2F169A-92DF-46ED-97E3-2F0BA82EC91A}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create and apply resource policies

2.  [Resource Locks
    > Guide](onenote:#5.2%20Resource%20Locks%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={E66C50A2-F1B0-4DF5-A582-2B7C6781439B}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > create resource locks

3.  [Role-based Access Control
    > (RBAC)](onenote:#6.%20Role-based%20Access%20Control%20(RBAC)&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={41D957D8-E5EA-4217-BC3D-F87C799A7163}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > learn about Azure RBAC

4.  [Azure Roles
    > Guide](onenote:#6.1%20Azure%20Roles%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={92943F76-474F-4382-8A19-0EF585B75266}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > apply roles

 

Links
=====

 

Common uses of Resource Manager policies:
<https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-subscription-governance>

![C:\\EFAC62E5\\2387C7B1-13D0-4026-92CB-129924B69776\_files\\image006.png](media/image6.png){width="14.791666666666666in"
height="1.5416666666666667in"}

 

 

6\. Role-based Access Control (RBAC)

Tuesday, December 12, 2017

9:37 AM

 

Description
===========

 

Azure Role-Based Access Control (RBAC) enables fine-grained access
management for Azure. Using RBAC, you can grant only the amount of
access that users need to perform their jobs.

 

![Machine generated alternative text: Account /Enterprise Agreement
Subscriptions Resource Groups Naming Standards and Tags Resource
Policies & Locks RBAC ](media/image1.png){width="14.822916666666666in"
height="9.666666666666666in"}

 

 

 

Design Considerations
=====================

 

-   Azure Roles when applied at subscription level are inherited into
    > resource groups and corresponding resources

-   The scope of where you assign azure roles is at the subscription,
    > resource group or resource level

-   Azure Role permissions can be assigned to user , groups or
    > applications

-   Azure has 65 Built-in roles (as of Dec. 15, 2017)

-   You can't modify the definitions of built-in roles. However, you can
    > create Custom roles in Azure RBAC to fit the specific needs of
    > your organization.

>  
>
>  

Proven Practices
================

 

-   Start with Top 10 most common roles and avoid complexity by defining
    > to many roles to start .

-   Connect your corporate identity store (most commonly Active
    > Directory) to Azure Active Directory using the AD Connect tool.

-   Control the Admin/Co-Admin of a subscription using a managed
    > identity. Don\'t assign Admin/Co-admin to a new subscription
    > owner. Instead, use RBAC roles to provide Owner rights to a group
    > or individual.

-   Add Azure users to a group (for example, Application X Owners) in
    > Active Directory. Use the synced group to provide group members
    > the appropriate rights to manage the resource group containing the
    > application.

-   Follow the principle of granting the least privilege required to do
    > the expected work. For example:

> Deployment Group: A group that is only able to deploy resources.
>
> Virtual Machine Management: A group that is able to restart VMs (for
> operations)

-   Use Azure Active Directory for Azure Governance roles

-   Use Built-In Roles before Custom Roles

> There are two primary reasons why these Custom Roles should be used:
>
> 1\. There is no existing built-in role to provide the role needed.
>
> 2\. An existing built-in role may exist, but gives away too many rights,
> and there is a need to reduce the rights to just the bare minimum.

-   Create Custom RBAC Roles only if Built-in does not exist

-   Use groups to assign RBAC versus users

-   Leverage Azure PIM to Govern Lifecycle of Azure Roles

-   Start small with key foundational roles and add roles as need arise

-   Implement JEA (just enough administration) and JIT (just in time)
    > role philosophy

-   Avoid assigning permanent roles

-   Set up alerts for role changes

>  

 

 

Next Steps
==========

1.  [Azure Roles
    > Guide](onenote:#6.1%20Azure%20Roles%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={92943F76-474F-4382-8A19-0EF585B75266}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one):
    > assign users or groups to built-in Azure roles.[6.1 Azure Roles
    > Guide](onenote:#6.1%20Azure%20Roles%20Guide&section-id={CE521654-5403-4F18-B2B2-A7C88AFF99EE}&page-id={92943F76-474F-4382-8A19-0EF585B75266}&end&base-path=https://microsoft.sharepoint.com/teams/AzureAccelerationTeam/SiteAssets/Azure%20Acceleration%20Team%20Notebook/Azure%20Subscription%20Design%20Tree%20v0.9.one)

>  

Links
=====

-   [Built-in roles for Azure role-based access
    > control](https://docs.microsoft.com/en-us/azure/active-directory/role-based-access-built-in-roles)

 

 

 

 

![C:\\EFAC62E5\\2387C7B1-13D0-4026-92CB-129924B69776\_files\\image007.png](media/image7.png){width="14.791666666666666in"
height="1.5416666666666667in"}

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

 
![Enrollment and Subscription](./enrollement-subcriptions-model.png)

 
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
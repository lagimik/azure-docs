\. Resources Groups

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
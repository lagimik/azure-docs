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

 

 
6\. Role-based Access Control (RBAC)

Tuesday, December 12, 2017

9:37 AM

 

Description
===========

 

Azure Role-Based Access Control (RBAC) enables fine-grained access
management for Azure. Using RBAC, you can grant only the amount of
access that users need to perform their jobs.


![Enrollment and Subscription](./enrollement-subcriptions-model.png)

 

 

 

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
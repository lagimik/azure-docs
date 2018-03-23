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

 

 
![Enrollment and Subscription](./enrollement-subcriptions-model.png)

 


 

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

 

1.  [Azure Tags Guide]()):
    > apply tags to resources

2.  [Resources Groups]( ):
    > Understand resource groups.

3.  [Resource Group Guide]( ):
    > define the resource group model and create resource groups.

4.  [Resource Policies & Locks]( ):
    > understand resource policies and locks

5.  [Resource Policy Guide]( ):
    > create and apply resource policies

6.  [Resource Locks Guide]():
    > create resource locks

7.  [Role-based Access Control (RBAC)]():
    > learn about Azure RBAC

8.  [Azure Roles Guide]():
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

 

 
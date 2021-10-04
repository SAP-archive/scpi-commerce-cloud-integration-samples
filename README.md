<!--
SPDX-FileCopyrightText: 2020 Pascal Barbier <pascal.barbier@sap.com>

SPDX-License-Identifier: Apache-2.0
-->

![](https://img.shields.io/badge/STATUS-NOT%20CURRENTLY%20MAINTAINED-red.svg?longCache=true&style=flat)

# Important Notice
This public repository is read-only and no longer maintained. For the latest sample code repositories, visit the [SAP Samples](https://github.com/SAP-samples) organization.

# Description
Documentation about SAP Commerce Integration using SAP Cloud Platform Integration (SCPI) with samples Iflows:

-   [Integrating Third-Party Applications](Integrating_Third-Party_Applications.md)
    -   [Define Integration Objects](Define_Integration_Objects.md)
        -   [Create an Integration Flow Triggered by SAP Commerce](Create_an_Integration_Flow_Triggered_by_SAP_Commerce.md)
            -   [Integration Scenarios: Commerce](Integration_Scenarios_Commerce.md)
        -   [Create an Integration Flow Triggered by SCPI](Create_an_Integration_Flow_Triggered_by_SCPI.md)
            -   [Integration Scenarios: SCPI](Integration_Scenarios_SCPI.md)


You'll find 2 sample packaged SCPI iflows in the iflows folder:
* [SendOrders.zip](../../releases/download/1.0.0/SendOrders.zip): A packaged SCPI iFlow illustrating an outbound integration scenario where SAP Commerce orders are transmitted to a third-party service for additional processing.
* [SendProductRatings.zip](../../releases/download/1.0.0/SendProductRatings.zip): A packaged SCPI iFlow illustrating an inbound integration scenario where a third-party service sends the SAP Commerce Product Catalog external data.

# Requirements
To import or design iFlows in [SCPI](https://help.sap.com/viewer/product/CLOUD_INTEGRATION):
* Admin/Developer rights on a running [SAP Commerce Cloud](https://help.sap.com/viewer/product/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD) instance version 19.05 or higher
To configure usage of deployed iFlows from/to SAP Commerce Cloud:
* Admin/Developer rights for a SCPI tenant
# Download and Installation
The packaged SCPI iFlows can be imported to a SCPI Tenant by following these steps:
From your SCPI Tenant access:
1. Open the SCPI **Design** view.
2. Create a new package by clicking **Create** at the right top of the page.
3. Click on the package.
4. Open the **Artifacts** tab.
5. Click **Edit**.
6. Click **Add**.
7. Select **IntegrationFlow**.
8. Select the **Upload** option. 
9. Click **Browse** and select one of the zip files in this repository.
10. (Optional) Change the name of the integration flow.
11. Click **OK**.

Once imported you can explore the different settings of the iFlow while going through the included PDF file.

# Limitations
The provided iFlows are examples that illustrate some integration principles in the context of SAP Commerce Cloud. You cannot run them as-is, as they are not relevant for any real third-party service.

They can, however, be used as a starting point or template for your own project.

Regarding the scope of your planned integration between SAP Commerce Cloud and other parties, we invite you to review the [Data Protection and Privacy section of SAP Commerce Security guide](https://help.sap.com/viewer/9433604f14ac4ed98908c6d4e7d8c1cc/1905/en-US/eff17b4180504a7d93134aa1d7c47a47.html) when starting your project.
# Known Issues
See **Limitations** section above
# How to obtain support
These sample iFlows are provided as-is, with no expected changes or support.
# License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt)

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/scpi-commerce-cloud-integration-samples)](https://api.reuse.software/info/github.com/SAP-samples/scpi-commerce-cloud-integration-samples)

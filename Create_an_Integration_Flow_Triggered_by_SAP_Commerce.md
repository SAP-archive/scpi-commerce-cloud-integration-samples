<!--
SPDX-FileCopyrightText: 2020 Pascal Barbier <pascal.barbier@sap.com>

SPDX-License-Identifier: Apache-2.0
-->

<!-- loio90be7ec1115a4f41b4aa03e5d1027b56 -->
<details><summary><b>Table of Contents</b></summary>
<p>

-   [Integrating Third-Party Applications](Integrating_Third-Party_Applications.md)
    -   [Define Integration Objects](Define_Integration_Objects.md)
        -   [Create an Integration Flow Triggered by SAP Commerce](Create_an_Integration_Flow_Triggered_by_SAP_Commerce.md)
            -   [Integration Scenarios: Commerce](Integration_Scenarios_Commerce.md)
        -   [Create an Integration Flow Triggered by SCPI](Create_an_Integration_Flow_Triggered_by_SCPI.md)
            -   [Integration Scenarios: SCPI](Integration_Scenarios_SCPI.md)

</p>
</details>

## Create an Integration Flow Triggered by SAP Commerce

You create a synchronous integration flow \(iFlow\) to define a process that happens to your data before it is exported to the third-party system.

1.  In SAP Cloud Platform Integration \(SCPI\), create an iFlow.

    For a list of example integration flows, see [Integration Scenarios: Commerce](Integration_Scenarios_Commerce.md).

2.  Deploy your iFlow.

3.  Configure Outbound Sync to SCPI.

    For more information, see **Outbound Sync to SCPI Integration Flow** at [https://help.sap.com/viewer/50c996852b32456c96d3161a95544cdb/1905/en-US/45c632aa498c42e4a93699b7a6d6d3f9.html](https://help.sap.com/viewer/50c996852b32456c96d3161a95544cdb/1905/en-US/45c632aa498c42e4a93699b7a6d6d3f9.html)

    > Note:
    > In the linked documentation, you see steps for creating an iFlow. You do not have to create another iFlow. You can simply add the correct configurations to the one you created at the start of this documentation.
    > 
    > 

4.  If required, configure a cron job to run the iFlow periodically.

    For more information, see **Scheduling Outbound Sync** at [https://help.sap.com/viewer/50c996852b32456c96d3161a95544cdb/1905/en-US/a537b2f1a1a644f09ba818b9bba311f9.html](https://help.sap.com/viewer/50c996852b32456c96d3161a95544cdb/1905/en-US/a537b2f1a1a644f09ba818b9bba311f9.html).

***

[Next: Integration Scenarios: Commerce -->](Integration_Scenarios_Commerce.md)

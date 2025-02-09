---
title: include file
description: include file
author: robinsh
ms.service: iot-hub
services: iot-hub
ms.topic: include
ms.date: 10/20/2021
ms.author: robinsh
ms.custom: include file
---
<!-- This tells how to get the connection string for the service shared access policy of your IoT hub -->

To get the IoT Hub connection string for the **service** policy, follow these steps:

1. In the [Azure portal](https://portal.azure.com), select **Resource groups**. Select the resource group where your hub is located, and then select your hub from the list of resources.

1. On the left-side pane of your IoT hub, select **Shared access policies**.

1. From the list of policies, select the **service** policy.

1. Under **Shared access keys**, select the copy icon for the **Primary connection string** and save the value.

:::image type="content" source="./media/iot-hub-include-find-service-connection-string/iot-hub-get-connection-string.png" alt-text="Show how to retrieve the connection string" border="true":::

For more information about IoT Hub shared access policies and permissions, see [Access control and permissions](../articles/iot-hub/iot-hub-dev-guide-sas.md#access-control-and-permissions).

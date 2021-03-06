---
author: DCtheGeek
ms.service: azure-policy
ms.topic: include
ms.date: 04/24/2020
ms.author: dacoulte
ms.custom: generated
---

|Name |Description |Policies |Version |
|---|---|---|---|
|[Container Registries should be encrypted with a Customer-Managed Key (CMK)](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2Fproviders%2FMicrosoft.Authorization%2FpolicyDefinitions%2F5b9159ae-1701-4a6f-9a7a-aa9c8ddd0580) |Audit Container Registries that do not have encryption enabled with Customer-Managed Keys (CMK). For more information on CMK encryption, please visit: [https://aka.ms/acr/CMK](https://aka.ms/acr/CMK). |Audit, Disabled |1.0.0-preview |[Link](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policyDefinitions/Container%20Registry/ACR_CMKEncryptionEnabled_Audit.json)
|[Container Registries should not allow unrestricted network access](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2Fproviders%2FMicrosoft.Authorization%2FpolicyDefinitions%2Fd0793b48-0edc-4296-a390-4c75d1bdfd71) |Audit Container Registries that do not have any Network (IP or VNET) Rules configured and allow all network access by default. Container Registries with at least one IP / Firewall rule or configured virtual network will be deemed compliant. For more information on Container Registry Network rules, please visit: [https://aka.ms/acr/vnet](https://aka.ms/acr/vnet). |Audit, Disabled |1.0.0-preview |[Link](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policyDefinitions/Container%20Registry/ACR_NetworkRulesExist_Audit.json)
|[Container Registry should use a virtual network service endpoint](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2Fproviders%2FMicrosoft.Authorization%2FpolicyDefinitions%2Fc4857be7-912a-4c75-87e6-e30292bcdf78) |This policy audits any Container Registry not configured to use a virtual network service endpoint. |Audit, Disabled |1.0.0-preview |[Link](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policyDefinitions/Network/VirtualNetworkServiceEndpoint_ContainerRegistry_Audit.json)

---
name: Azure Virtual Network
description: Azure Virtual Network lets you create private networks in the cloud with
  full control over IP addresses, DNS servers, security rules, and traffic flows.
  Securely connect a virtual network to on-premises networks by using a VPN tunnel,
  or connect privately by using the ExpressRoute service.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Network
- Microsoft
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/azure-virtual-network/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Virtual Network API
  description: Azure Virtual Network lets you create private networks in the cloud
    with full control over IP addresses, DNS servers, security rules, and traffic
    flows
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/azure-virtual-network/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-network-localnetworkgateways-get.md
- name: Azure Virtual Network API Virtual Network Gateways Get
  description: Gets the specified virtual network gateway by resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: http:://management.azure.com//
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/azure-virtual-network/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-network-virtualnetworkgateways-virtualnetworkgatewayname-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/azure-virtual-network/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-network-virtualnetworkgateways-virtualnetworkgatewayname-get-postman.md
- name: Azure Virtual Network API Local Network Gateways List
  description: Gets all the local network gateways in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: http:://management.azure.com//
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/azure-virtual-network/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-network-localnetworkgateways-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/azure-virtual-network/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-network-localnetworkgateways-get-postman.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/virtual-network/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/virtual-network/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/virtual-network/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/virtual-network/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/virtual-network/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/virtual-network/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
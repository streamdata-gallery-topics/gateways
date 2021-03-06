---
name: AWS Storage Gateway Service
description: The AWS Storage Gateway service seamlessly enables hybrid storage between
  on-premises storage environments andnbsp;the AWS Cloud. It combines a multi-protocol
  storage appliance with highly efficient network connectivity tonbsp;Amazon cloud
  storagenbsp;services, deliveringnbsp; local performance with virtually unlimited
  scale. Customers use it in remote offices and datacenters for hybrid cloud workloads,
  backup and restore, archive, disaster recovery, and tiered storage.nThe Storage
  Gateway virtual appliance connects seamlessly to your local infrastructure as a
  file server, as a volume, or as a virtual tape library (VTL). This seamless connection
  makes it simple for organizations to augment existing on-premises storage investments
  with the high scalability, extreme durability and low cost of cloud storage. nbsp;
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Gateway
- Deployment
- Database
- Data
- Amazon Web Services
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/aws-storage-gateway-service/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS Storage Gateway Service API
  description: The AWS Storage Gateway service seamlessly enables hybrid storage between
    on-premises storage environments andnbsp;the AWS Cloud
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: ""
  baseURL: :///
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/aws-storage-gateway-service/action-listgateways-get.md
- name: AWS Storage Gateway Service API List Gateways
  description: Lists gateways owned by an AWS account in a region specified in the
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: http:://{host}//
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/aws-storage-gateway-service/action-listgateways-get.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/storagegateway/latest/APIReference
- type: x-faq
  url: https://aws.amazon.com/storagegateway/faqs/
- type: x-pricing
  url: https://aws.amazon.com/storagegateway/pricing/
- type: x-website
  url: https://aws.amazon.com/storagegateway/
- type: x-documentation
  url: http://docs.aws.amazon.com/storagegateway/latest/APIReference
- type: x-faq
  url: https://aws.amazon.com/storagegateway/faqs/
- type: x-pricing
  url: https://aws.amazon.com/storagegateway/pricing/
- type: x-website
  url: https://aws.amazon.com/storagegateway/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
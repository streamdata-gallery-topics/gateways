---
name: AWS Direct Connect
description: AWS Direct Connect makes it easy to establish a dedicated network connection
  from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity
  between AWS and your datacenter, office, or colocation environment, which in many
  cases can reduce your network costs, increase bandwidth throughput, and provide
  a more consistent network experience than Internet-based connections.nAWS Direct
  Connect lets you establish a dedicated network connection between your network and
  one of the AWS Direct Connect locations. Using industry standard 802.1q VLANs, this
  dedicated connection can be partitioned into multiple virtual interfaces. This allows
  you to use the same connection to access public resources such as objects stored
  in Amazon S3 using public IP address space, and private resources such as Amazon
  EC2 instances running within annbsp;Amazon Virtual Private Cloud (VPC)nbsp;using
  private IP space, while maintaining network separation between the public and private
  environments. Virtual interfaces can be reconfigured at any time to meet your changing
  needs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Networks
- Network
- Amazon Web Services
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/aws-direct-connect/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS Direct Connect API
  description: AWS Direct Connect makes it easy to establish a dedicated network connection
    from your premises to AWS
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: ""
  baseURL: :///
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/aws-direct-connect/action-describevirtualgateways-get.md
- name: AWS Direct Connect API Describe Virtual Gateways
  description: Returns a list of virtual private gateways owned by the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: http:://{host}//
  tags: Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gateways/master/_listings/aws-direct-connect/action-describevirtualgateways-get.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Direct-Connect
- type: x-console
  url: https://console.aws.amazon.com/directconnect/
- type: x-documentation
  url: http://docs.aws.amazon.com/directconnect/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/directconnect/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=126
- type: x-getting-started
  url: https://aws.amazon.com/directconnect/getting-started/
- type: x-partner-bundles
  url: ttps://aws.amazon.com/directconnect/directconnectbundles/
- type: x-partners
  url: https://aws.amazon.com/directconnect/partners/
- type: x-pricing
  url: https://aws.amazon.com/directconnect/pricing/
- type: x-website
  url: https://aws.amazon.com/directconnect/
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Direct-Connect
- type: x-console
  url: https://console.aws.amazon.com/directconnect/
- type: x-documentation
  url: http://docs.aws.amazon.com/directconnect/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/directconnect/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=126
- type: x-getting-started
  url: https://aws.amazon.com/directconnect/getting-started/
- type: x-partner-bundles
  url: ttps://aws.amazon.com/directconnect/directconnectbundles/
- type: x-partners
  url: https://aws.amazon.com/directconnect/partners/
- type: x-pricing
  url: https://aws.amazon.com/directconnect/pricing/
- type: x-website
  url: https://aws.amazon.com/directconnect/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
---
name: AWS Direct Connect
x-slug: aws-direct-connect
description: AWS Direct Connect makes it easy to establish a dedicated network connection
  from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity
  between AWS and your datacenter, office, or colocation environment, which in many
  cases can reduce your network costs, increase bandwidth throughput, and provide
  a more consistent network experience than Internet-based connections.AWS Direct
  Connect lets you establish a dedicated network connection between your network and
  one of the AWS Direct Connect locations. Using industry standard 802.1q VLANs, this
  dedicated connection can be partitioned into multiple virtual interfaces. This allows
  you to use the same connection to access public resources such as objects stored
  in Amazon S3 using public IP address space, and private resources such as Amazon
  EC2 instances running within anAmazon Virtual Private Cloud (VPC)using private IP
  space, while maintaining network separation between the public and private environments.
  Virtual interfaces can be reconfigured at any time to meet your changing needs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Direct Connect
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Direct Connect API - Allocate Connection On Interconnect
  x-api-slug: actionallocateconnectiononinterconnect-get
  description: Creates a hosted connection on an interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actionallocateconnectiononinterconnect-get-openapi.md
- name: AWS Direct Connect API - Allocate Private Virtual Interface
  x-api-slug: actionallocateprivatevirtualinterface-get
  description: Provisions a private virtual interface to be owned by a different customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actionallocateprivatevirtualinterface-get-openapi.md
- name: AWS Direct Connect API - Allocate Public Virtual Interface
  x-api-slug: actionallocatepublicvirtualinterface-get
  description: Provisions a public virtual interface to be owned by a different customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actionallocatepublicvirtualinterface-get-openapi.md
- name: AWS Direct Connect API - Confirm Connection
  x-api-slug: actionconfirmconnection-get
  description: Confirm the creation of a hosted connection on an interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actionconfirmconnection-get-openapi.md
- name: AWS Direct Connect API - Confirm Private Virtual Interface
  x-api-slug: actionconfirmprivatevirtualinterface-get
  description: Accept ownership of a private virtual interface created by another
    customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actionconfirmprivatevirtualinterface-get-openapi.md
- name: AWS Direct Connect API - Confirm Public Virtual Interface
  x-api-slug: actionconfirmpublicvirtualinterface-get
  description: Accept ownership of a public virtual interface created by another customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actionconfirmpublicvirtualinterface-get-openapi.md
- name: AWS Direct Connect API - Create B G P Peer
  x-api-slug: actioncreatebgppeer-get
  description: Creates a new BGP peer on a specified virtual interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actioncreatebgppeer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actioncreatebgppeer-get-openapi.md
- name: AWS Direct Connect API - Create Connection
  x-api-slug: actioncreateconnection-get
  description: Creates a new connection between the customer network and a specific
    AWS Direct Connect location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actioncreateconnection-get-openapi.md
- name: AWS Direct Connect API - Create Interconnect
  x-api-slug: actioncreateinterconnect-get
  description: Creates a new interconnect between a AWS Direct Connect partner's network
    and a specific AWS Direct Connect location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actioncreateinterconnect-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actioncreateinterconnect-get-openapi.md
- name: AWS Direct Connect API - Create Private Virtual Interface
  x-api-slug: actioncreateprivatevirtualinterface-get
  description: Creates a new private virtual interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actioncreateprivatevirtualinterface-get-openapi.md
- name: AWS Direct Connect API - Create Public Virtual Interface
  x-api-slug: actioncreatepublicvirtualinterface-get
  description: Creates a new public virtual interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actioncreatepublicvirtualinterface-get-openapi.md
- name: AWS Direct Connect API - Delete B G P Peer
  x-api-slug: actiondeletebgppeer-get
  description: Deletes a BGP peer on the specified virtual interface that matches
    the specified customer address and ASN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondeletebgppeer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondeletebgppeer-get-openapi.md
- name: AWS Direct Connect API - Delete Connection
  x-api-slug: actiondeleteconnection-get
  description: Deletes the connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondeleteconnection-get-openapi.md
- name: AWS Direct Connect API - Delete Interconnect
  x-api-slug: actiondeleteinterconnect-get
  description: Deletes the specified interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondeleteinterconnect-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondeleteinterconnect-get-openapi.md
- name: AWS Direct Connect API - Delete Virtual Interface
  x-api-slug: actiondeletevirtualinterface-get
  description: Deletes a virtual interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondeletevirtualinterface-get-openapi.md
- name: AWS Direct Connect API - Describe Connection Loa
  x-api-slug: actiondescribeconnectionloa-get
  description: Returns the LOA-CFA for a Connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribeconnectionloa-get-openapi.md
- name: AWS Direct Connect API - Describe Connections
  x-api-slug: actiondescribeconnections-get
  description: Displays all connections in this region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribeconnections-get-openapi.md
- name: AWS Direct Connect API - Describe Connections On Interconnect
  x-api-slug: actiondescribeconnectionsoninterconnect-get
  description: Return a list of connections that have been provisioned on the given
    interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribeconnectionsoninterconnect-get-openapi.md
- name: AWS Direct Connect API - Describe Interconnect Loa
  x-api-slug: actiondescribeinterconnectloa-get
  description: Returns the LOA-CFA for an Interconnect.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribeinterconnectloa-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribeinterconnectloa-get-openapi.md
- name: AWS Direct Connect API - Describe Interconnects
  x-api-slug: actiondescribeinterconnects-get
  description: Returns a list of interconnects owned by the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribeinterconnects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribeinterconnects-get-openapi.md
- name: AWS Direct Connect API - Describe Locations
  x-api-slug: actiondescribelocations-get
  description: Returns the list of AWS Direct Connect locations in the current AWS
    region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribelocations-get-openapi.md
- name: AWS Direct Connect API - Describe Tags
  x-api-slug: actiondescribetags-get
  description: Describes the tags associated with the specified Direct Connect resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribetags-get-openapi.md
- name: AWS Direct Connect API - Describe Virtual Gateways
  x-api-slug: actiondescribevirtualgateways-get
  description: Returns a list of virtual private gateways owned by the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribevirtualgateways-get-openapi.md
- name: AWS Direct Connect API - Describe Virtual Interfaces
  x-api-slug: actiondescribevirtualinterfaces-get
  description: Displays all virtual interfaces for an AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiondescribevirtualinterfaces-get-openapi.md
- name: AWS Direct Connect API - Tag Resource
  x-api-slug: actiontagresource-get
  description: Adds the specified tags to the specified Direct Connect resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actiontagresource-get-openapi.md
- name: AWS Direct Connect API - Untag Resource
  x-api-slug: actionuntagresource-get
  description: Removes one or more tags from the specified Direct Connect resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AWSDirectConnect.png
  humanURL: https://aws.amazon.com/directconnect/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Profiles, Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-direct-connect/master/_listings/aws-direct-connect/actionuntagresource-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.device.farm.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.direct.connect.stack.network
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
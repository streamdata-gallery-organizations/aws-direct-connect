---
swagger: "2.0"
x-collection-name: AWS Direct Connect
x-complete: 0
info:
  title: AWS Direct Connect API Create Interconnect
  version: 1.0.0
  description: Creates a new interconnect between a AWS Direct Connect partner's network
    and a specific AWS Direct Connect location.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AllocateConnectionOnInterconnect:
    get:
      summary: Allocate Connection On Interconnect
      description: Creates a hosted connection on an interconnect.
      operationId: allocateConnectionOnInterconnect
      x-api-path-slug: actionallocateconnectiononinterconnect-get
      parameters:
      - in: query
        name: bandwidth
        description: Bandwidth of the connection
        type: string
      - in: query
        name: connectionName
        description: Name of the provisioned connection
        type: string
      - in: query
        name: interconnectId
        description: ID of the interconnect on which the connection will be provisioned
        type: string
      - in: query
        name: ownerAccount
        description: Numeric account Id of the customer for whom the connection will
          be provisioned
        type: string
      - in: query
        name: vlan
        description: The dedicated VLAN provisioned to the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=AllocatePrivateVirtualInterface:
    get:
      summary: Allocate Private Virtual Interface
      description: Provisions a private virtual interface to be owned by a different
        customer.
      operationId: allocatePrivateVirtualInterface
      x-api-path-slug: actionallocateprivatevirtualinterface-get
      parameters:
      - in: query
        name: connectionId
        description: The connection ID on which the private virtual interface is provisioned
        type: string
      - in: query
        name: newPrivateVirtualInterfaceAllocation
        description: Detailed information for the private virtual interface to be
          provisioned
        type: string
      - in: query
        name: ownerAccount
        description: The AWS account that will own the new private virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Private Virtual Interfaces
  /?Action=AllocatePublicVirtualInterface:
    get:
      summary: Allocate Public Virtual Interface
      description: Provisions a public virtual interface to be owned by a different
        customer.
      operationId: allocatePublicVirtualInterface
      x-api-path-slug: actionallocatepublicvirtualinterface-get
      parameters:
      - in: query
        name: connectionId
        description: The connection ID on which the public virtual interface is provisioned
        type: string
      - in: query
        name: newPublicVirtualInterfaceAllocation
        description: Detailed information for the public virtual interface to be provisioned
        type: string
      - in: query
        name: ownerAccount
        description: The AWS account that will own the new public virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Private Virtual Interfaces
  /?Action=ConfirmConnection:
    get:
      summary: Confirm Connection
      description: Confirm the creation of a hosted connection on an interconnect.
      operationId: confirmConnection
      x-api-path-slug: actionconfirmconnection-get
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=ConfirmPrivateVirtualInterface:
    get:
      summary: Confirm Private Virtual Interface
      description: Accept ownership of a private virtual interface created by another
        customer.
      operationId: confirmPrivateVirtualInterface
      x-api-path-slug: actionconfirmprivatevirtualinterface-get
      parameters:
      - in: query
        name: virtualGatewayId
        description: ID of the virtual private gateway that will be attached to the
          virtual interface
        type: string
      - in: query
        name: virtualInterfaceId
        description: ID of the virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Private Virtual Interfaces
  /?Action=ConfirmPublicVirtualInterface:
    get:
      summary: Confirm Public Virtual Interface
      description: Accept ownership of a public virtual interface created by another
        customer.
      operationId: confirmPublicVirtualInterface
      x-api-path-slug: actionconfirmpublicvirtualinterface-get
      parameters:
      - in: query
        name: virtualInterfaceId
        description: ID of the virtual interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Private Virtual Interfaces
  /?Action=CreateBGPPeer:
    get:
      summary: Create B G P Peer
      description: Creates a new BGP peer on a specified virtual interface.
      operationId: createBGPPeer
      x-api-path-slug: actioncreatebgppeer-get
      parameters:
      - in: query
        name: newBGPPeer
        description: Detailed information for the BGP peer to be created
        type: string
      - in: query
        name: virtualInterfaceId
        description: The ID of the virtual interface on which the BGP peer will be
          provisioned
        type: string
      responses:
        200:
          description: OK
      tags:
      - BGP Peer
  /?Action=CreateConnection:
    get:
      summary: Create Connection
      description: Creates a new connection between the customer network and a specific
        AWS Direct Connect location.
      operationId: createConnection
      x-api-path-slug: actioncreateconnection-get
      parameters:
      - in: query
        name: bandwidth
        description: Bandwidth of the connection
        type: string
      - in: query
        name: connectionName
        description: The name of the connection
        type: string
      - in: query
        name: location
        description: Where the connection is located
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connections
  /?Action=CreateInterconnect:
    get:
      summary: Create Interconnect
      description: Creates a new interconnect between a AWS Direct Connect partner's
        network and a specific AWS Direct Connect location.
      operationId: createInterconnect
      x-api-path-slug: actioncreateinterconnect-get
      parameters:
      - in: query
        name: bandwidth
        description: The port bandwidth
        type: string
      - in: query
        name: interconnectName
        description: The name of the interconnect
        type: string
      - in: query
        name: location
        description: Where the interconnect is located
        type: string
      responses:
        200:
          description: OK
      tags:
      - Interconnects
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---